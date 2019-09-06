# Observations Offerings Identifier

**Purpose**: Test that the Observations Offerings have an Identifier, and it is a unique URI according to OGC SWE Service Model.

**Prerequisites**

**Test method**

* Send a GetCapabilities request.

    * For every [Observation Offering](#observationOffering) node:

        * Check that child element [Identifier](#identifier) exists for every observation.
        
    * Check that the values of the [Identifier](#identifier) elements are not repeated in the Capabilities document.

    * If any validation fails then the test fails.

**Reference(s)**:

* [INS TG SOS](http://inspire.ec.europa.eu/id/document/tg/download-sos/1.0), Requirements 4.4

**Test type**: Automated

**Notes**

The multiplicity of [Observation Offering](#observationOffering) is 0 to n.

The multiplicity of [Identifier](#identifier) is 1 for each [Observation Offering](#observationOffering).

## Contextual XPath references

The namespace prefixes used as described in [README](./README.md#namespaces).

| Abbreviation                                               |  XPath expression (relative to /sos:Capabilities) |
| ---------------------------------------------------------- | ------------------------------------------------------------------------- |
| Observation Offering <a name="observationOffering"></a> | sos:contents/sos:Contents/swes:offering/sos:ObservationOffering |
| Identifier <a name="identifier"></a> | sos:contents/sos:Contents/swes:offering/sos:ObservationOffering/swes:identifier |
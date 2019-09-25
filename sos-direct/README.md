# Conformance class: Direct SOS (DRAFT)

This conformance class is part of the [Abstract Test Suite for the INSPIRE Download Services Technical Guidance](http://inspire.ec.europa.eu/id/ats/download-sos/1.0).

## Standardization target type

OGC web service (SOS 2.0)

## Dependencies

### Direct dependencies

A direct dependency is another conformance class whose requirements must be met by the download service.

| Specification | Conformance class | Parameters | 
| ------------- | ----------------- | ---------- |
| [OGC SOS](#ref_OGC_SOS) | SOS Core | n/a |
| [FES 2.0.0](#ref_FES) | Query | n/a |

### Indirect dependencies

none
 
## External document references

| Abbreviation | Document name                       |
| ------------ | ----------------------------------- |
| INSPIRE <a name="ref_INSPIRE"></a> | [Directive 2007/2/EC of the European Parliament and of the Council of 14 March 2007 establishing an Infrastructure for Spatial Information in the European Community (INSPIRE)](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32007L0002&from=EN)
| IR NS <a name="ref_IR_NS"></a>   | [Commission Regulation (EC) No 976/2009 of 19 October 2009 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards the Network Services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32009R0976&from=EN)
| INS TG SOS <a name="ref_INS_TG_SOS"></a>   | [Technical Guidance for implementing download services using the OGC Sensor Observation Service and ISO 19143 Filter Encoding](http://inspire.ec.europa.eu/id/document/tg/download-sos/1.0) 
| OGC SOS <a name="ref_OGC_SOS"></a> | [OGC 12-006 Sensor Observation Service Interface Standard](https://portal.opengeospatial.org/files/?artifact_id=47599)
| FES 2.0 <a name="ref_FES"></a> | [OpenGIS Filter Encoding 2.0 Encoding Standard](http://portal.opengeospatial.org/files/?artifact_id=39968)

## TG Requirement coverage

Based on requirement numbering in [INS TG SOS](#ref_INS_TG_SOS).

| Req#   | Description                          | Covered by test(s)                 |
| ------ | ------------------------------------ | ---------------------------------- |
| 5.1    | Implementations SHALL conform to the [OGC SOS] Conformance Class ‘SOS Core’ and meet TG Requirement 4.2, TG Requirement 4.3, and TG Requirement from 4.6 to 4.15 | [OGC SOS](#ref_OGC_SOS) 14.1.1 SOS Core, [OGC SOS](#ref_OGC_SOS) 14.5.1 SOS Spatial Filtering Profile, [OGC SOS](#ref_OGC_SOS) 14.6.1 XML Encoding and 14.6.2 KVP Binding Extension, [at4-06-extended-capabilities](../sos-pre-defined/at4-06-extended-capabilities.md), [at4-07-observations-offerings-lang-namespace-crs](../sos-pre-defined/at4-07-observations-offerings-lang-namespace-crs.md), [at4-08-crs-observation](../sos-pre-defined/at4-08-crs-observation.md), [at4-09-language-capabilities-supported](../sos-pre-defined/at4-09-language-capabilities-supported.md), [at4-10-language-capabilities-request](../sos-pre-defined/at4-10-language-capabilities-request.md), [at4-11-language-capabilities-parameter](../sos-pre-defined/at4-11-language-capabilities-parameter.md), [at4-12-language-capabilities-default](../sos-pre-defined/at4-12-language-capabilities-default.md), [at4-13-language-capabilities-response](../sos-pre-defined/at4-13-language-capabilities-response.md), [at4-14-language-capabilities-list](../sos-pre-defined/at4-14-language-capabilities-list.md), [at4-15-extended-capabilities-xml-schema](../sos-pre-defined/at4-15-extended-capabilities-xml-schema.md) |
| 5.2    | A Direct Access Download Service SHALL implement the GetObservationByID operation | [OGC SOS](#ref_OGC_SOS) 14.2.2 SOS Observation Retrieval By Id |

## Tests
The Conformance class "Direct SOS: Implement Direct Access Download Service (“Parts A, B & C”) using Sensor Observation Service" is covered by the tests shown in the previous section. Therefore there is not specific tests for this conformance class.

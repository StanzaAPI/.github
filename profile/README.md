# Stanza API

Deterministic micro-APIs for validating and parsing regulated financial, healthcare, and supply-chain data. Built on Cloudflare Workers with sub-15ms edge latency.

## APIs

| API | Description |
| --- | --- |
| [IBAN & BIC/SWIFT Validator](https://stanzaapi.com/tools/iban-validator) | ISO 13616 IBAN and ISO 9362 BIC validation, MOD-97 checksums, bank code extraction |
| [EU & UK VAT Validator](https://stanzaapi.com/tools/vat-validator) | VAT number format and checksum validation with current rate data |
| [Global LEI Validator](https://stanzaapi.com/tools/lei-validator) | ISO 17442 LEI, US EIN, Australian ABN, and UK CRN validation |
| [ISO 20022 Parser](https://stanzaapi.com/tools/iso20022-parser) | Parse and convert pacs.008, camt.053, and pain.001 messages to JSON |
| [Peppol BIS Billing Validator](https://stanzaapi.com/tools/peppol-validator) | Peppol BIS 3.0 and EN 16931 e-invoice validation and parsing |
| [Healthcare X12 Parser](https://stanzaapi.com/tools/x12-parser) | ANSI X12 837, 835, and 270/271 EDI parsing to JSON |
| [UDI Decoder](https://stanzaapi.com/tools/udi-decoder) | FDA GUDID and EU MDR UDI barcode decoding (GS1, HIBCC, ICCBBA) |
| [DSCSA Verifier](https://stanzaapi.com/tools/pharma-dscsa) | FDA DSCSA and EU FMD pharmaceutical serialization verification |
| [GS1 Decoder](https://stanzaapi.com/tools/gs1-decoder) | GS1 barcode element strings and Digital Link URIs |
| [IATA Validator](https://stanzaapi.com/tools/iata-validator) | Air waybill, e-ticket, and baggage tag validation |
| [Container Validator](https://stanzaapi.com/tools/container-validator) | ISO 6346 container check-digit and size/type validation |
| [CBAM Calculator](https://stanzaapi.com/tools/cbam-carbon) | EU CBAM embedded emissions and carbon tax calculation |

## Clients

Official zero-dependency clients for Python, TypeScript, Rust, and C# are published from this organization, one repository per API and language.

- Website: https://stanzaapi.com
- Documentation: https://stanzaapi.com/docs
- Pricing: https://stanzaapi.com/pricing
- OpenAPI specs: `https://api.stanzaapi.com/<api-slug>/openapi.json`

## Engineering

- [Engineering notes](https://github.com/StanzaAPI/engineering-notes): a public log of experiments, failures, and what changed afterward.
- [Benchmark harness](https://github.com/StanzaAPI/benchmark-harness): reproducible throughput and memory benchmarks, including a head-to-head of the X12 parser against established open-source alternatives.
- [X12 test data](https://github.com/StanzaAPI/x12-test-data): deterministic synthetic corpora plus cataloged adversarial cases for testing X12 parsers.


## Contact

- Support: support@stanzaapi.com
- Security: security@stanzaapi.com

# Tradeweb

Tradeweb Markets is a leading global operator of electronic marketplaces for rates, credit, equities, and money markets. The platform provides APIs for electronic trading execution, market data, trade reporting, and integration with order management and risk systems across more than 40 fixed income and derivatives products.

**Website:** https://www.tradeweb.com/  
**Integration:** https://www.tradeweb.com/our-markets/institutional/integration/  
**Client Area:** https://www.tradeweb.com/client-area/

## APIs

Tradeweb offers client-specific API access through a dedicated development team. APIs are not publicly documented and require a client relationship.

| API | Description |
|-----|-------------|
| Trading API | Electronic execution across fixed income, derivatives, and ETF markets via RFQ, click-to-trade, and AiEX workflows |
| Python API | Direct connection between Python trading models and Tradeweb execution |
| FIX API | FIX protocol connectivity for OMS, EMS, and STP integration |
| Market Data API | Real-time and historical OTC pricing across 20+ asset classes |
| APA Trade Reporting API | MiFID II post-trade transparency reporting via Approved Publication Arrangement |

## Artifacts

### Spectral Rules

| File | Description |
|------|-------------|
| [tradeweb-spectral-rules.yml](rules/tradeweb-spectral-rules.yml) | Spectral ruleset enforcing Tradeweb API conventions |

### JSON Schemas

| File | Description |
|------|-------------|
| [tradeweb-trade-schema.json](json-schema/tradeweb-trade-schema.json) | Schema for executed trade data |
| [tradeweb-rfq-schema.json](json-schema/tradeweb-rfq-schema.json) | Schema for RFQ session and quotes |

### JSON Structure

| File | Description |
|------|-------------|
| [tradeweb-trade-structure.json](json-structure/tradeweb-trade-structure.json) | Structure documentation for trade objects |

### JSON-LD

| File | Description |
|------|-------------|
| [tradeweb-context.jsonld](json-ld/tradeweb-context.jsonld) | JSON-LD context for Tradeweb linked data semantics |

### Examples

| File | Description |
|------|-------------|
| [tradeweb-rfq-example.json](examples/tradeweb-rfq-example.json) | Example RFQ session with dealer quotes |

### Vocabulary

| File | Description |
|------|-------------|
| [tradeweb-vocabulary.yaml](vocabulary/tradeweb-vocabulary.yaml) | Domain vocabulary for Tradeweb electronic trading concepts |

## Features

| Name | Description |
|------|-------------|
| Request for Quote (RFQ) | Send RFQs to multiple dealers simultaneously for competitive pricing on fixed income and derivatives. |
| Automated Intelligent Execution (AiEX) | Automated trade execution with pre-defined rules for straight-through processing. |
| Click-to-Trade | One-click trade execution on streaming dealer prices. |
| Market Data | Real-time and historical pricing data across 20+ asset classes. |
| Trade Reporting (APA) | MiFID II compliant post-trade transparency reporting via Approved Publication Arrangement. |
| Straight-Through Processing | Automated post-trade processing from execution to settlement. |
| Python API | Direct connection between Python trading models and Tradeweb execution. |
| FIX Connectivity | Industry-standard FIX protocol integration with OMS, EMS, and risk systems. |
| Multi-Asset Coverage | Trading across rates, credit, equities, ETFs, and money markets on a single platform. |
| Pre-Trade Analytics | Transaction cost analysis and liquidity analytics before trade execution. |

## Maintainers

- **Kin Lane** (kin@apievangelist.com)

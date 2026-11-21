# Ammons Data Labs

Small, working tools for keeping research and working knowledge searchable: ingestion, indexing,
retrieval, and the context an LLM works from.

---

## Current

### [context-collector](https://github.com/ammons-datalabs/adl-context-collector)

A personal MCP server that gives any MCP-compatible LLM client persistent, portable memory.

- Semantic search over captured notes, decisions and documents (PostgreSQL + pgvector)
- Structured facts with temporal tracking: an update keeps the earlier value, readable as of a past date
- Ingestion of Markdown, PDF, plain text and GitHub issues
- Identifier-aware search, so a query for PR 204 finds PR 204 rather than PR 267
- Separate vaults (for example, work and personal) on one installation
- Fully local operation with Ollama, so no data leaves the machine

Start from the [adl-context-vault](https://github.com/ammons-datalabs/adl-context-vault) template.

### [PhD Corpus Ingestion & Search](https://github.com/ammons-datalabs/adl-pdf-ingest-phd)

A compact ingestion pipeline for a research PDF corpus: text extraction and cleaning, metadata
enrichment, repeatable database-backed runs, and full-text search.

---

## Earlier work

Reference implementations from 2025, not under active development:

- [Observable Agent Starter](https://github.com/ammons-datalabs/observable-agent-starter): agent template with tracing and evaluation in CI (DSPy, Langfuse, DeepEval)
- [RoleSkills](https://github.com/ammons-datalabs/RoleSkills): skill evidence extraction and scoring from repos and role specs
- [adl-docs-service](https://github.com/ammons-datalabs/adl-docs-service): .NET 8 document summarisation backend
- [HoldThatThread](https://github.com/ammons-datalabs/HoldThatThread): .NET 9 streaming reasoning API
- [ADL M365 Automation Starter](https://github.com/ammons-datalabs/adl-m365-automation-starter): invoice automation with Azure and Teams
- [adl-ba-screening](https://github.com/ammons-datalabs/adl-ba-screening): GIS property screening service (flood overlays, parcel metrics)

## Archived research

- [Evaluate-SCAIL](https://github.com/ammons-datalabs/Evaluate-SCAIL): petabyte-scale encrypted deduplication with segment chunks and sorted indexing (PhD codebase, kept for reproducibility)

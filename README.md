# Nurzhan Serikbekov

Backend developer from Astana, Kazakhstan. Almost three years of Python in production
across government, oil & gas and enterprise systems. Master's student at Astana IT
University, researching retrieval-augmented generation for regulatory documents.

**Stack:** Python, Django / DRF, FastAPI, PostgreSQL (PostGIS, pgvector), SQL Server,
Celery, Redis, Docker. Some React.

## Work

Most of my commercial code is under NDA, so this is what it does rather than the code:

- **National education database.** SQL Server of about 11 TB with tables up to 2 billion
  rows: query and index tuning, bulk operations, long jobs moved to Celery.
- **Workflow systems.** Electronic work orders with approvals, role-based access and
  digital signatures (NCALayer, CMS); a procurement and pricing service synced daily
  with a data warehouse.
- **Integrations.** State registries, 1C, SAP, SOAP services, LDAP / Active Directory,
  Keycloak.
- **GIS portal for telecom infrastructure.** FastAPI and PostGIS on the backend,
  React and Leaflet on the front.

## Projects

- [regulatory-agent-system](https://github.com/nurzhvn52/regulatory-agent-system) -
  research platform for evidence-grounded agents over Kazakhstan's regulatory acts:
  legal-structure chunking, BM25 / BGE-M3 / hybrid retrieval on pgvector, a cited-QA
  agent that checks its own sources, a reproducible benchmark. FastAPI, SQLAlchemy,
  Alembic, pytest, mypy.
- [rag-citizen-appeals](https://github.com/nurzhvn52/rag-citizen-appeals) - code and
  results for my IEEE DG 2026 paper: can clusters replace the metadata that anonymization
  removes from citizen appeals? Short answer: it depends on the embedder.
- [product-stats-api](https://github.com/nurzhvn52/product-stats-api) - Django REST
  service: product import, pandas normalization, PostgreSQL, Celery Beat, Redis cache,
  Docker Compose, tests.

## Research

*A RAG-based Intelligent Agent for Analyzing Citizen Appeals in the Context of Regulatory
and Administrative Documentation* - IEEE DG 2026, accepted, first author.

## Contact

Telegram [@nurzhvn](https://t.me/nurzhvn) · serikbekov2004@mail.ru

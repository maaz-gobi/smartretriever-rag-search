# SmartRetriever — Features

A detailed look at what SmartRetriever does. (Marketing documentation — no implementation details.)

## Hybrid Retrieval

SmartRetriever doesn't rely on a single search method:

- **Vector / semantic search** — finds content by *meaning*, so a query and a document match even when they use different words.
- **Keyword search** — finds *exact* terms: names, identifiers, codes, and specific phrases.
- **Combined ranking** — results draw on both, giving you relevance and precision together.

## Document Ingestion

- Supports PDF and DOCX documents.
- Builds a searchable knowledge base from your files.
- Handles large collections, not just single documents.

## Retrieval-Augmented Generation

- Answers are generated *from* retrieved source content.
- Reduces hallucination compared to ungrounded AI answers.
- Results stay traceable to the documents they came from.

## Automated Report Generation

- Compiles retrieved content into structured reports.
- Template-driven output for consistency.
- Turns a research question into a finished document.

## Deployment

- Containerized with Docker for portable, consistent setup.
- Runs the same way across environments.

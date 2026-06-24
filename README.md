# 📊 Advanced RAG Pipeline: Complex Legal Ingestion & Statistical Semantic Chunking

This repository contains an advanced Retrieval-Augmented Generation (RAG) pipeline tailored for high-density, messy legal documents (specifically archived court opinions from `case.law`). It addresses the structural limitations of naive chunking by implementing statistical semantic parsing and context-aware dynamic window expansion.

---

## 🏗️ System Architecture & Execution Pipeline

```mermaid
graph TD
    A([1. Environment & Theme Setup]) --> B[/2. Complex Legal Ingestion/]
    B --> C[3. Statistical Semantic Boundaries]
    C --> D[4. Metadata Context Enrichment]
    D --> E[5. DB Inversion & Token Audit]
    E --> F[/6. Target Query Vectorization/]
    F --> G{7. Metadata Filter Selection}
    G --> H[8. Contextual Window Expansion]
    H --> I[9. Grounded Legal Synthesis]
    I --> J([10. Final Answer with Citations])

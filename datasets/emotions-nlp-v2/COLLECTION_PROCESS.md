# Collection Process - Emotions NLP v2

## Source Selection
The raw data for version 2.0 was aggregated from a diverse set of public domain sources, including:
- Curated social media threads from 2024-2025.
- Creative Commons licensed literature extracts.
- Synthetic augmentations to ensure class balance.

## Annotation Workflow
1. **Initial Tagging:** Data was initially tagged using a high-accuracy zero-shot model.
2. **Human Review:** Each entry was reviewed by three independent human annotators.
3. **Consensus:** A label was only assigned if at least two out of three annotators agreed. In cases of 0% agreement, the entry was discarded.
4. **Validation:** A final audit was performed by Lead Data Architects at Kryonara Lab to ensure 100% schema compliance.

## Data Cleaning
- **Deduplication:** Fuzzy matching was used to remove near-identical entries.
- **Normalization:** Standardized punctuation and whitespace.
- **PII Scrubbing:** Any personally identifiable information (names, emails, phones) was replaced with generic tokens or removed.

---
© 2026 Kryonara AI Lab

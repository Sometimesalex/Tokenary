# Tokenary
This is a Token based library to aid semantic processing and interpretation.


# Tokenary

Tokenary is an open-source project that converts dictionary and reference knowledge into structured, machine-readable tokens.

The goal is to provide a stable, auditable layer between natural language sources (such as dictionaries and encyclopedias) and AI systems, reducing ambiguity, hallucination, and loss of context.

---

## Why Tokenary Exists

Current AI systems rely heavily on unstructured text. This causes well-known problems:

- inconsistent reasoning
- hallucinated or conflated facts
- loss of context across sessions
- difficulty distinguishing “unknown” from “not applicable”

Tokenary addresses this by representing knowledge as explicit JSON structures with fixed fields and clear semantics.

---

## What Is a Token?

A Tokenary token is a JSON object with a fixed schema that describes an entity using:

- taxonomy and classification
- physical or abstract attributes
- cognitive and social properties (where applicable)
- capabilities and constraints

Tokens are designed to be:
- deterministic
- auditable
- reusable across systems
- independent of any single AI model

---

## Data Sources

Tokenary is designed to be populated using:

- GCIDE (GNU Collaborative International Dictionary of English)
- modern dictionary references (e.g. Merriam-Webster–style definitions)
- encyclopedic knowledge (Wikipedia-level)

Data enrichment is intentional and controlled. The schema is never altered.

---

## Project Status

- Token schema defined
- Sample tokens implemented
- Conversion scripts in progress
- Bulk data population pending sustained tooling access

---

## Planned Output

- A–Z Tokenary packages derived from GCIDE
- Public JSON datasets
- Reusable tooling for structured knowledge generation

---

## Public Benefit

Tokenary is intended for:

- AI safety and reliability research
- knowledge representation
- education and digital literacy
- open data reuse

The project is open-source and designed for public reuse.

---

## License

Open-source. License to be finalised.

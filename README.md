# Minimal Ethical Governance (MEG) Protocol
![MEG Logo](https://github.com/meg-initiative/meg/blob/main/meg_logo.png)

**Motto: Ethics becomes real when it can be implemented.**

---

# Minimal Ethical Governance (MEG)

MEG is an open, engine-agnostic technical and legal governance framework for AI systems, including agentic and multi-agent applications.

The current framework consists of two complementary layers:

- **MEG1 (MEG v5.0) - Technical Standard**  
  Defines the technical evidence, audit, behavioral assurance, identity, delegation and control mechanisms.

- **MEG2 - Legal Governance Framework**  
  Assigns legal and accountability significance to the evidence produced by MEG1, including persistent agent identity, delegation chains, guarantees, jurisdiction and graduated liability.

MEG is designed as a voluntary implementation-layer standard. It does not replace existing regulation, product liability, sectoral rules or contractual obligations.

## Current status

The current authoritative framework is:

- MEG1 v5.0
- MEG2 Legal Governance Framework
- MEG2 Case Studies
- MEG Core Overview
- MEG Executive Summary
- Theoretical Foundations of MEG

The current documents are available in:

```text
meg1-meg2/
```

The earlier MEG v4.6.2 specifications remain available in:

```text
specs/
```

They are retained for historical and version-traceability purposes and are not the current standard.

## Core architecture

MEG separates technical evidence from legal accountability.

```text
AI system or agent
        ↓
MEG1 technical evidence layer
        ↓
identity, delegation, controls, audit records,
EFR, DAI, ISR, DEA and credential evidence
        ↓
MEG2 legal governance layer
        ↓
authority, responsibility, guarantee,
jurisdiction and liability allocation
```

## Main mechanisms

### MEG Address

A persistent technical and legal identifier for an AI system or agent, implemented through interoperable identity and credential mechanisms such as W3C DID and Verifiable Credentials.

### Ethical Flight Recorder

A protected forensic evidence mechanism for material incidents, designed to support post-incident reconstruction without requiring disclosure of full proprietary model data.

### DAI, ISR and DEA

Versioned behavioral and assurance indicators used to measure reliability, safety, responsibility and demonstrated autonomy.

### Delegation and authority controls

Machine-readable delegation chains, scope limitations and architectural human-confirmation mechanisms.

### Liability Container

A legal and operational construct linking an identified system to obligations, guarantees and accountability mechanisms.

## Repository structure

```text
meg/
├── meg1-meg2/
│   ├── MEG1 v5.0
│   ├── MEG2
│   ├── MEG2 Case Studies
│   ├── MEG Core
│   ├── Executive Summary
│   └── Theoretical Foundations
├── specs/
│   └── legacy MEG v4.6.2 specifications
├── CONTRIBUTING.md
├── LICENCE
└── README.md
```

## Current implementation resources

### MEG Registry

A public reference implementation of MEG Address and credential verification:

- https://registry.meg-initiative.org/

The current registry is a sandbox reference implementation. Its credentials are self-attested and carry no legal or regulatory weight.

### Inspect AI evaluation package

An executable implementation of initial DAI and ISR evaluation tasks:

- https://github.com/meg-initiative/meg-inspect-eval

This package provides deterministic scorers, local fixture datasets, automated tests and a reproducible offline baseline.

### Legacy SDK

The earlier SDK prototype for MEG v4.6–v4.7 is archived here:

- https://github.com/meg-initiative/meg-sdk

It is not compatible with MEG1 v5.0 or MEG2 and must not be treated as the current implementation.

## Publications

- MEG1 v5.0 Technical Standard  
  https://doi.org/10.5281/zenodo.21280680

- MEG2 Legal Governance Framework  
  https://doi.org/10.5281/zenodo.21280676

- MEG Core / Executive materials  
  https://doi.org/10.5281/zenodo.21280688

Full public library:

- https://meg-initiative.org/library/

## Licensing

The MEG specifications and documentation are licensed under Creative Commons Attribution 4.0 International, unless a file states otherwise.

You may copy, redistribute, adapt and use the material commercially, provided appropriate attribution is given and modifications are indicated.

Software repositories may use separate software licences, such as MIT.

## Citation

When citing MEG, use the relevant document DOI and identify the version used.

Suggested general attribution:

```text
Adrian Stan, MEG Initiative, Minimal Ethical Governance,
MEG1 v5.0 and MEG2, 2026.
```

## Contributing

Technical corrections, implementation proposals, test cases and interoperability contributions are welcome.

Before proposing a change, identify whether it concerns:

- the current MEG1 v5.0 technical layer;
- the MEG2 legal layer;
- the executable Inspect evaluation package;
- the Registry reference implementation;
- legacy MEG v4.6.2 materials.

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Disclaimer

MEG is an open technical and legal governance framework.

Use of MEG does not by itself constitute certification, regulatory conformity, legal compliance, insurance coverage or proof that an AI system is safe.


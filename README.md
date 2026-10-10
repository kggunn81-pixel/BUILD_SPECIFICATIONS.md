There are 49 app build instructions, app24 is the master workbench  to contain all other apps as one, app 49 applies to all apps as it automatically fills in inputs into each app.The project has a set of policy documents that state how data is handled, how the project is governed, and how it is sustained.

Philosophy of Science Meets Software — Computational Tooling for STAG, Null-Model & Provenance
About
This repository contains the full build specifications for an open-source suite of 24 software tools for computational philosophy of science. The tools address two problems:

How to annotate scale-dependent scientific claims so that distinctions between derivation, representation, evidence, counterfactual dependence, and interpretation are preserved. This is the STAG (Scale-Transition Annotation Graph) framework.

How to test empirical gap claims against an explicitly specified null model, accounting for selection effects, measurement uncertainty, dependence, and the search over candidate gaps. This is the Null-Model Protocol.

The suite is designed to be used together. STAG records the annotation; the Null-Model Protocol tests the statistical claim; the shared infrastructure stores, queries, and reproduces both.

Status
This is a specification and pre-registration project, not a validated software product. The 24 build specifications are complete. The code has not been written yet. Contributions are welcome.

The 24 tools
Annotation and authoring tools

STAG Annotation Editor — builds one STAG annotation record from start to finish.

STAG Annotation Validator — checks an annotation file against the schemas and the 32 semantic rules.

PROV-O Exporter and Importer — converts a STAG record to and from PROV-O.

Scale-Separation Record Calculator — builds and checks one scale-separation record.

Graph and visualisation tools

STAG Graph Viewer — interactive viewer for a complete STAG.

Partition Sensitivity Explorer — re-derives labels under an alternative partition.

Revision History Viewer — timeline view of a STAG's revision chain.

Null-Model Protocol tools

Pipeline Specification Wizard — produces a machine-readable pipeline specification.

Full-Pipeline Simulator — the core engine of the Null-Model Protocol.

Scan-Family Comparator — runs the same data under several scan families and reports calibration and power side by side.

Effective-Null Builder — constructs the effective null after selection and measurement.

N Calculator — plans a simulation run.

Gap-Score Reporter — descriptive-only tool for screening candidate gaps.

Integrated platforms

STAG plus Null-Model Combined Workbench — one environment that uses both documents together.

Journal Submission Checker — checks a submission against the two reporting standards.

Teaching and Training Sandbox — interactive environment with the worked examples preloaded.

Libraries and infrastructure

STAG Schema Library — the schemas and rules as a versioned package.

Null-Model Protocol Library — the protocol as a versioned software library.

Reproducibility Deposit Template — a template repository for reproducible deposits.

Provenance-Aware Annotation Database — a store for annotation collections.

Review and audit tools

STAG Audit Tool — runs the checklist audit against a submitted document.

Numerical Verification Tool — checks reported numbers against declared sources.

Repository and index

Physics Knowledge Library — a provenance-aware, versioned repository of non-fiction works.

Master Workbench — a plugin host and index for all 23 modules.

Repository structure
text
.
├── README.md                       # this file
├── BUILD_SPECIFICATIONS.md         # the full build specifications for all 24 tools
├── specs/                          # individual specification files (if split)
│   ├── 01-stag-annotation-editor.md
│   ├── 02-stag-annotation-validator.md
│   └── ...
├── docs/                           # documentation, guides, tutorials
├── examples/                       # worked examples
├── schemas/                        # JSON Schema and SHACL schema files
├── codebook/                       # the STAG codebook and Null-Model Protocol specification
└── CONTRIBUTING.md                 # how to contribute
If you have not created the specs/, docs/, examples/, schemas/, or codebook/ folders yet, that is fine. You can add them later. The repository structure section describes the intended layout.

How to use this repository
If you want to build one of the tools:

Read the build specification for that tool in BUILD_SPECIFICATIONS.md or in specs/.

Read the source documents the tool is based on. The STAG specification is in codebook/. The Null-Model Protocol is in codebook/. The schemas are in schemas/.

Open an issue to say which tool you are building.

Build it. Follow the build phases in the specification.

Submit a pull request.

If you want to use one of the tools:

The tools are not built yet. When they are, this section will be updated with installation and usage instructions.

If you want to review or improve a specification:

Open an issue describing the change you propose. Specifications are versioned; changes are tracked.

Background
The project is based on two methodological proposals:

Artifact 1 — Main Paper. Scale-Transition Annotation Graphs (STAG): A Methodological Framework and Scoping-Review Protocol for Annotating Scale-Dependent Organization.

Artifact 2 — Codebook and Schema. The operational instrument of the STAG framework: field list, permitted value sets, semantic validation rules, and machine-readable schemas.

Artifact 3 — Response to Hostile Readings. The framework's replies to objections that a hostile referee may raise.

Null-Model Protocol. A Null-Model Protocol for Statistical Gap Claims in Scale-Dependent Data.

These documents are the source material for the 24 build specifications. They are deposited in this repository under codebook/.

What this project is not
It is not a validated software product.

It is not a replacement for any established physical theory or statistical method.

It is not a finished system. It is a specification and pre-registration project.

It does not claim that any annotation is currently evidentially anchored.

It does not claim that any statistical gap is physically significant.

How to contribute
Contributions are welcome. You do not need to be an expert in philosophy of science, statistics, or software engineering. You need to be willing to read a specification carefully and build something that matches it.

Ways to contribute:

Build a tool from a specification.

Review a specification and suggest improvements.

Test a tool and report bugs.

Write documentation or tutorials.

Share the project with someone who might be interested.

Before you start, read CONTRIBUTING.md. If you are unsure where to start, open an issue and ask.

License
MIT License

Copyright (c) 2026 Keith Gunn

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Citation
Citation information will be added when the specifications are deposited on Zenodo. Until then, please cite this repository.

Keith Gunn. (2026). Philosophy of Science Meets Software — Computational Tooling for STAG, Null-Model & Provenance. GitHub.

Contact
Facebook group: Philosophy of Science Meets Software — Computational Tooling for STAG, Null-Model & Provenance

Email: kggunn81@gmail.com

Acknowledgments
This project is a specification and pre-registration effort. It builds on decades of work in philosophy of science, effective field theory, renormalization-group methods, multiscale modelling, formal ontology, and scan statistics. The references are in the source documents.



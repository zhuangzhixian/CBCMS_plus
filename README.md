# **CBCMS+: Cross-Border Compliance Management System Plus**

## Overview

Modern software systems must increasingly operate across multiple jurisdictions, where legal compliance has become a critical and complex requirement. The challenge lies in encoding diverse legal obligations into precise, actionable, and context-aware policies throughout the software development lifecycle.

**CBCMS+ (Cross-Border Compliance Management System Plus)** addresses this challenge by providing a structured, scalable, and automated framework for cross-border compliance policy generation. It integrates key components—including the **Policy Definition Language (PDL)**, the **Enhanced PDL Mapping Pipeline (EpMap)**, and the **Compliance Policy Generator (ComGen)**—to support trustworthy and regulation-aware software engineering across global regulatory contexts.

### Key Features

- **Policy Definition Language (PDL):** Provides a unified, machine-processable format to represent both regulatory constraints and user-defined data processing preferences.
- **EpMap (Enhanced PDL Mapping):** Maps multilingual legal provisions into structured PDL fields using a structure-preserving mapping pipeline.
- **ComGen (Compliance Policy Generator):** Generates contextualized, executable compliance policies from attributes like data categories, sensitivity levels, and jurisdictional scopes.
- **High Scalability and Efficiency:** Achieves real-time policy generation under high-concurrency workloads, enabling practical integration into DevOps workflows.

## Open Source Commitment

To promote transparency, reproducibility, and community collaboration, we have publicly released the following core components of CBCMS+:

1. **[EpMap: Enhanced PDL Mapping Pipeline](https://github.com/zhuangzhixian/EpMap_CBCMS_plus)**
    This repository contains:
   - Source code for EpMap, which performs fine-grained mapping from legal text to structured PDL representations.
   - A detailed annotation manual specifying annotating rules and label semantics used during model training.
2. **[ComGen: Compliance Policy Generator](https://github.com/zhuangzhixian/ComGen_CBCMS_plus)**
    This repository contains:
   - Source code for ComGen, which generates valid PDL policy templates based on structured input attributes.
   - A comprehensive annotation manual describing data schemas and PDL policy formats.

### Why We Open Sourced These Components

EpMap and ComGen form the foundation of CBCMS+, enabling automated, regulation-aware policy generation in diverse environments. Open-sourcing these modules allows us to:

- Promote reproducibility of our results and workflows.
- Enable broader adaptation of compliance-by-design practices across jurisdictions.
- Foster research and innovation in software compliance automation.

## How to Get Started

1. Visit the individual repositories for EpMap and ComGen:
   - [EpMap Repository](https://github.com/zhuangzhixian/EpMap_CBCMS_plus)
   - [ComGen Repository](https://github.com/zhuangzhixian/ComGen_CBCMS_plus)
2. Follow the `README.md` in each repository for setup instructions, usage examples, and training guidance.
3. Refer to the annotation manuals for dataset preparation and consistent labeling practices.

## Acknowledgements

We thank all collaborators and reviewers who contributed to the design and development of CBCMS+. We also acknowledge the broader community for ongoing efforts in promoting transparent, auditable, and compliant software systems.

For questions or feedback, please contact:

- **Email:** [zhuangzhixian22s@ict.ac.cn](mailto:zhuangzhixian22s@ict.ac.cn)

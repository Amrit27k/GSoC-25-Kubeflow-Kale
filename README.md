# GSoC-25-Kubeflow-Kale
This repo contains my application proposal and details regarding GSoC'25 under Kubeflow

# 🚀 Project: JupyterLab Plugin for Kubeflow

## ✨ Overview

This project successfully modernized the architecture of **Kubeflow Kale**, a JupyterLab extension that allows users to define and run Kubeflow Pipelines directly from Jupyter notebooks. The key focus was migrating the backend from the deprecated **Kubeflow Pipelines v1 (KFPv1)** to the modern **KFPv2** architecture, accompanied by a comprehensive overhaul of the frontend and related development practices.

---

## 💻 Key Outcomes

The modernization effort resulted in the following key achievements:

* **KFPv2 Backend Migration:** Rebuilt the Kale backend to fully support the modern, future-proof **Kubeflow Pipelines v2 (KFPv2)** architecture, providing enhanced stability and features.
* **Intelligent Notebook Conversion:** Implemented a new **Jinja2 templating system** that intelligently converts annotated Jupyter notebook cells into valid **KFPv2 Python DSL scripts**, streamlining the notebook-to-pipeline process.
* **Modernized JupyterLab Frontend:** Updated the JupyterLab frontend extension using current standards, including **Typescript v5.9.2**, **Jupyterlab v4**, and **MUI v7**, which resolved hundreds of legacy compatibility issues and improved user experience.
* **Enhanced Metadata and Artifact Handling:** Integrated KFPv2's robust system for better **type-safe artifact handling** and **automated ML Metadata registration**, ensuring rich lineage tracking and reproducibility for pipeline steps.
* **Community Standardization:** Standardized the project structure, updated GitHub workflows, and implemented UI test scripts to align with current community standards, significantly enhancing **maintainability** for future contributors.

---

## 👥 Contributors & Mentors

* **Contributor:** Amrit Kumar (`@Amrit27k`)
* **Mentors:** Eder Ignatowicz (`@ederign`), Stefano Fioravanzo (`@StefanoFioravanzo`)

---

## 🔗 Resources

| Resource Type | Link |
| :--- | :--- |
| **Project Repository** | [Kubeflow Kale](https://github.com/kubeflow/kale) |
| **Project Roadmap** | [Kubeflow Kale 2.0 - Project Roadmap](link-to-roadmap-document) |
| **Project Blog** | [From Notebooks to Pipelines: My GSoC’25 Journey Modernizing Kubeflow Kale with KFPv2 and Jupyterlabv4](link-to-blog-post) |

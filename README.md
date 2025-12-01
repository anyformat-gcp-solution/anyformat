# Anyformat – Document Gen-AI Platform on Google Cloud

Anyformat is a cloud-native Gen-AI document automation platform built on Google Cloud, enabling enterprises to transform unstructured documents into structured, machine-ready intelligence with high accuracy and full auditability. The platform provides a high-precision parsing API, automated workflows, and monitoring with audit-grade explainability. It leverages Cloud Run, Vertex AI, Cloud Storage, BigQuery, Cloud Functions, and Firestore to deliver scalable, compliant, and end-to-end document automation for industries such as financial services, healthcare, government, and professional services.

## 🚀 Key Capabilities

- Gen-AI powered document parsing API  
- End-to-end workflow automation  
- LLM + vision model orchestration using Vertex AI  
- Audit-grade explainability for regulated industries  
- Document types supported: PDFs, scans, contracts, forms, reports  
- Full observability and traceability across document pipelines  

## 🏗 Google Cloud Architecture

```mermaid
flowchart LR
    A[Document Upload] --> B[Cloud Storage - Ingestion Bucket]
    B --> C[Cloud Run - Ingestion Service]
    C --> D[Vertex AI - Parsing & Classification]
    D --> E[Cloud Run - Workflow Orchestrator]
    E --> F[BigQuery - Structured Output]
    E --> G[Firestore - Workflow State & Audit Logs]
    E --> H[Cloud Functions - Integrations / Webhooks]

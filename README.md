<p align="center">
  <img src="banner.png" alt="Patient Planet Care Intelligence Platform" width="100%">
</p>

<!-- ====================================================================== -->
<!--                                                                       -->
<!--                     PATIENT PLANET CARE INTELLIGENCE PLATFORM          -->
<!--                                                                       -->
<!-- ====================================================================== -->

<div align="center">

# Patient Planet Care Intelligence Platform

### Enterprise AI Operating System for Homecare, Care Homes & Distributed Care Networks

*Transforming operational data into organizational intelligence.*

---

![Platform](https://img.shields.io/badge/Platform-Enterprise-blue)
![Development](https://img.shields.io/badge/Status-Active%20Development-success)
![Frontend](https://img.shields.io/badge/Frontend-Next.js-black)
![Backend](https://img.shields.io/badge/Backend-FastAPI-green)
![Language](https://img.shields.io/badge/Python-3.12-blue)
![Database](https://img.shields.io/badge/PostgreSQL-16-blue)
![AI](https://img.shields.io/badge/AI-OpenAI-purple)
![Infrastructure](https://img.shields.io/badge/Infrastructure-Docker-2496ED)
![License](https://img.shields.io/badge/License-Proprietary-red)

</div>

---

## Overview

Patient Planet Care Intelligence Platform is an enterprise software platform designed specifically for organizations delivering care outside the traditional hospital environment.

The platform enables homecare providers and care homes to manage operations, workforce, quality, compliance, assessments, reporting and executive decision-making through a single integrated operating system.

Rather than replacing existing workflows, Patient Planet connects operational information across the organization and transforms it into actionable intelligence through executive dashboards, artificial intelligence and predictive analytics.

The platform currently consists of two enterprise products built on a shared intelligence architecture:

🏠 **Homecare Intelligence**

🏡 **Care Home Intelligence**

Together they provide a unified operational view across clinical services, workforce management, regulatory compliance, quality systems and executive performance.

---

# Why Patient Planet Exists

Healthcare is rapidly moving beyond hospitals.

Homecare providers, care homes, assisted living communities and hospital-at-home programs are becoming essential components of modern healthcare delivery.

As organizations grow, so does operational complexity.

Scheduling systems, HR software, compliance documentation, quality audits, assessments, financial reports and operational data often exist in separate systems, requiring leadership teams to consolidate information manually before decisions can be made.

Patient Planet was built to simplify this complexity.

Instead of navigating multiple software platforms, leaders gain a single operational view of their organization through one enterprise platform.

The objective is straightforward:

• Improve operational visibility

• Strengthen quality management

• Standardize compliance

• Support workforce performance

• Reduce organizational risk

• Enable faster and better executive decision-making

Without changing how care teams deliver care.

---

# Platform Philosophy

Patient Planet has been designed around a simple engineering principle.

```

Operational Systems record activity.

↓

Intelligence Systems enable decisions.

```

Most healthcare software answers one question.

> **What happened?**

Patient Planet is designed to answer five.

```

What is happening?

↓

Why is it happening?

↓

What is likely to happen next?

↓

What should be done?

↓

How can performance continuously improve?

```

This architectural philosophy guides every module within the platform.

Rather than building isolated software products, Patient Planet brings together operational workflows, quality systems, compliance management, workforce intelligence and artificial intelligence into one enterprise operating system.

---
---

# Platform Architecture

Patient Planet follows a modular enterprise architecture designed around clear separation of concerns.

Each layer has a defined responsibility while remaining independently extensible.

```text

                                      PATIENT PLANET
                           Care Intelligence Platform Architecture

═══════════════════════════════════════════════════════════════════════════════════════════════════════

                                      USERS

                     Executives • Managers • Nurses • Caregivers
                     Auditors • Quality Teams • Administrators

═══════════════════════════════════════════════════════════════════════════════════════════════════════
                                              │
                                              ▼

┌───────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                         PRESENTATION LAYER                                        │
├───────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                   │
│  Next.js App Router                                                                               │
│  React                                                                                             │
│  TypeScript                                                                                        │
│  TailwindCSS                                                                                       │
│                                                                                                   │
│  • Executive Command Centre                                                                       │
│  • Homecare Intelligence                                                                          │
│  • Care Home Intelligence                                                                         │
│  • AI Co-Pilot                                                                                    │
│  • Dashboards                                                                                     │
│  • Reports                                                                                        │
│                                                                                                   │
└───────────────────────────────────────────────────────────────────────────────────────────────────┘
                                              │
                                              ▼

┌───────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                     APPLICATION SERVICES                                          │
├───────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                   │
│ Authentication │ Authorization │ Business Logic │ Validation │ Reporting │ API Layer             │
│                                                                                                   │
│ FastAPI • Python                                                                                  │
│                                                                                                   │
└───────────────────────────────────────────────────────────────────────────────────────────────────┘
                                              │
                     ┌────────────────────────┼────────────────────────┐
                     ▼                        ▼                        ▼

┌─────────────────────────────┐   ┌─────────────────────────────┐   ┌─────────────────────────────┐
│       DATA PLATFORM         │   │      AI SERVICES            │   │      FILE SERVICES          │
├─────────────────────────────┤   ├─────────────────────────────┤   ├─────────────────────────────┤
│ PostgreSQL                  │   │ OpenAI                      │   │ Upload Management           │
│ SQLAlchemy                  │   │ Prompt Orchestration        │   │ Evidence Repository         │
│ Alembic                     │   │ AI Co-Pilot                │   │ Generated Reports           │
│ Audit Trail                 │   │ Recommendations             │   │ Attachments                │
└─────────────────────────────┘   └─────────────────────────────┘   └─────────────────────────────┘
                     │                        │                        │
                     └────────────────────────┼────────────────────────┘
                                              ▼

┌───────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 CARE INTELLIGENCE ENGINE                                          │
├───────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                   │
│  Executive Intelligence                                                                           │
│  Operational Intelligence                                                                         │
│  Workforce Intelligence                                                                           │
│  Quality Intelligence                                                                             │
│  Compliance Intelligence                                                                          │
│  Benchmark Intelligence                                                                           │
│  Predictive Risk Analytics                                                                        │
│  AI Decision Support                                                                              │
│  Reporting & Insights                                                                             │
│                                                                                                   │
└───────────────────────────────────────────────────────────────────────────────────────────────────┘
                                              │
                                              ▼

┌───────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                    ENTERPRISE MODULES                                             │
├───────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                   │
│  🏠 Homecare Intelligence                                                                         │
│  🏡 Care Home Intelligence                                                                        │
│                                                                                                   │
└───────────────────────────────────────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════════════════════════════════════
```

---

# Platform Components

Patient Planet is composed of several independent but tightly integrated enterprise services.

```text

Patient Planet

├── Executive Command Centre
│   ├── CEO Dashboard
│   ├── Executive KPIs
│   ├── Operational Snapshot
│   ├── Performance Monitoring
│   └── Enterprise Reporting
│
├── Homecare Intelligence
│   ├── Patient Management
│   ├── Caregiver Management
│   ├── Scheduling
│   ├── Clinical Operations
│   ├── Assessments
│   └── Service Delivery
│
├── Care Home Intelligence
│   ├── Resident Management
│   ├── Occupancy
│   ├── Daily Operations
│   ├── Resident Safety
│   ├── Incident Management
│   └── Facility Operations
│
├── Quality Intelligence
│   ├── Quality Management System
│   ├── Digital Assessments
│   ├── Internal Audits
│   ├── Continuous Improvement
│   └── Clinical Governance
│
├── Compliance Intelligence
│   ├── NABH Standards Mapping
│   ├── Digital Compliance Workflow
│   ├── Automated NC Detection
│   ├── AI-assisted CAPA
│   ├── Evidence Management
│   └── Audit Readiness
│
├── Workforce Intelligence
│   ├── Staff Management
│   ├── Performance Monitoring
│   ├── Competency Tracking
│   ├── Productivity Analytics
│   └── Training Records
│
├── Risk Intelligence
│   ├── Patient Risk Monitoring
│   ├── Resident Risk Monitoring
│   ├── Predictive Analytics
│   ├── Early Warning Indicators
│   └── Escalation Management
│
├── AI Services
│   ├── AI Co-Pilot
│   ├── Natural Language Queries
│   ├── Recommendation Engine
│   ├── Document Intelligence
│   └── Decision Support
│
└── Reporting Engine
    ├── Operational Reports
    ├── Executive Reports
    ├── Benchmark Reports
    ├── Quality Reports
    └── Compliance Reports

```

---

# Design Principles

The platform has been engineered around a set of architectural principles.

```text

✓ Modular Architecture

✓ Domain-Driven Design

✓ API-First Development

✓ AI-Native Workflows

✓ Multi-Tenant Ready

✓ Security by Design

✓ Compliance by Design

✓ Scalable Service Boundaries

✓ Enterprise Extensibility

✓ Standards-Based Interoperability

✓ Separation of Presentation, Business Logic and Data

✓ Executive-First User Experience

```

The architecture is intentionally modular to allow new intelligence domains, regulatory frameworks, AI capabilities and enterprise integrations to be introduced without affecting the core platform.

---

# Repository Architecture

The repository is organized around modular enterprise domains.

Each domain encapsulates its own API endpoints, business services, data models and validation logic, allowing the platform to evolve without creating unnecessary coupling between modules.

```text

patient-planet-care-intelligence
│
├── backend
│   │
│   ├── alembic
│   │   ├── versions
│   │   └── env.py
│   │
│   ├── sql
│   │
│   └── app
│       │
│       ├── api
│       │   ├── authentication
│       │   ├── executive
│       │   ├── homecare
│       │   ├── carehome
│       │   ├── compliance
│       │   ├── quality
│       │   ├── workforce
│       │   ├── reporting
│       │   ├── ai
│       │   └── administration
│       │
│       ├── core
│       │   ├── configuration
│       │   ├── security
│       │   ├── permissions
│       │   └── middleware
│       │
│       ├── db
│       │
│       ├── models
│       │
│       ├── schemas
│       │
│       ├── services
│       │
│       ├── intelligence
│       │
│       ├── reporting
│       │
│       ├── integrations
│       │
│       ├── templates
│       │
│       └── utils
│
├── frontend
│   │
│   ├── app
│   ├── components
│   ├── hooks
│   ├── lib
│   ├── services
│   ├── styles
│   ├── public
│   └── assets
│
├── storage
│   ├── uploads
│   ├── evidence
│   └── reports
│
├── docker
│
├── docs
│
├── scripts
│
└── README.md

```

---

# Domain Architecture

Patient Planet follows a domain-oriented architecture.

Each business capability is developed as an independent domain while sharing common platform services such as authentication, reporting, AI orchestration and security.

```text

                                   Patient Planet

                                          │

      ┌───────────────────────────────────┼────────────────────────────────────┐

      ▼                                   ▼                                    ▼

 Homecare Domain                 Care Home Domain                  Executive Domain

      │                                   │                                    │

      ├── Patients                      ├── Residents                     ├── KPIs

      ├── Visits                        ├── Occupancy                     ├── Dashboards

      ├── Care Plans                    ├── Daily Care                    ├── Analytics

      ├── Assessments                   ├── Incidents                     ├── Reports

      └── Scheduling                    └── Facility Ops                  └── Insights

      ┌───────────────────────────────────┼────────────────────────────────────┐

      ▼                                   ▼                                    ▼

 Quality Domain                 Compliance Domain               Workforce Domain

      │                                   │                                    │

      ├── QMS                          ├── NABH                          ├── Staff

      ├── Audits                       ├── NC                            ├── Training

      ├── Assessments                  ├── CAPA                          ├── Competency

      ├── Indicators                   ├── Evidence                      ├── Performance

      └── Monitoring                   └── Readiness                     └── Productivity

                                          │

                                          ▼

                              Shared Intelligence Services

                                          │

      ├── AI Co-Pilot

      ├── Reporting Engine

      ├── Benchmark Engine

      ├── Risk Engine

      ├── Notification Services

      ├── Authentication

      ├── Authorization

      └── Audit Logging

```

---

# Intelligence Workflow

Patient Planet continuously transforms operational activity into executive intelligence.

```text

                    DATA SOURCES

      Patient Records

      Resident Records

      Workforce Data

      Compliance Data

      Quality Assessments

      Incidents

      Operations

      Documents

               │

               ▼

══════════════════════════════════════════════

          DATA VALIDATION LAYER

══════════════════════════════════════════════

               │

               ▼

══════════════════════════════════════════════

       CARE INTELLIGENCE ENGINE

══════════════════════════════════════════════

      Data Correlation

      Business Rules

      Risk Scoring

      Trend Detection

      Predictive Analytics

      AI Recommendations

      Benchmark Analysis

      Operational Insights

══════════════════════════════════════════════

               │

               ▼

══════════════════════════════════════════════

        EXECUTIVE DECISION LAYER

══════════════════════════════════════════════

      Executive Dashboards

      AI Co-Pilot

      Quality Alerts

      Compliance Monitoring

      Workforce Insights

      Performance KPIs

      Professional Reports

      Strategic Decision Support

```

---

# Engineering Principles

Patient Planet has been designed around engineering principles intended to support long-term maintainability, scalability and enterprise adoption.

```text

Architecture Philosophy

├── Modular Design
├── Domain-Driven Development
├── API-First Architecture
├── AI-Native Platform
├── Multi-Tenant Ready
├── Cloud-Native Deployment
├── Security by Design
├── Compliance by Design
├── Privacy by Design
├── Separation of Concerns
├── Service-Oriented Architecture
├── Extensible Module Design
├── Standards-Based Interoperability
├── Comprehensive Auditability
└── Enterprise Scalability

```

---

# Development Roadmap

```text

Version 1.0
│
├── Homecare Intelligence
├── Care Home Intelligence
├── Executive Command Centre
├── AI Co-Pilot
├── Quality Management System
├── NABH Digital Workflow
├── Compliance Intelligence
├── Workforce Intelligence
└── Professional Reporting

──────────────────────────────────────────────

Version 2.0
│
├── Multi-Tenant Architecture
├── Enterprise RBAC
├── DPDP Compliance Framework
├── ISO 27001 Readiness
├── SOC 2 Readiness
├── Advanced Analytics
├── Benchmark Intelligence
└── API Integrations

──────────────────────────────────────────────

Version 3.0
│
├── FHIR Interoperability
├── Healthcare Knowledge Graph
├── Agentic AI Workflows
├── Population Health Intelligence
├── Enterprise Integrations
├── AI Workflow Automation
├── Cross-Organization Benchmarking
└── Global Regulatory Frameworks

```

---

# Security & Platform Architecture

Patient Planet is designed using layered security principles suitable for enterprise healthcare environments.

Security is treated as a platform capability rather than a standalone feature, with controls applied across identity, application services, data access and infrastructure.

```text

                                  SECURITY MODEL

══════════════════════════════════════════════════════════════════════════════════════

                               Identity & Access

══════════════════════════════════════════════════════════════════════════════════════

 Users
    │
    ▼
Authentication
    │
    ▼
Role Based Access Control (RBAC)
    │
    ▼
Permission Evaluation
    │
    ▼
Business Services

══════════════════════════════════════════════════════════════════════════════════════

                              Application Security

══════════════════════════════════════════════════════════════════════════════════════

Input Validation
        │
        ▼
Business Rules
        │
        ▼
Authorization
        │
        ▼
Audit Logging
        │
        ▼
Database

══════════════════════════════════════════════════════════════════════════════════════

```

---

# Multi-Tenant Architecture

The platform is designed to support multiple organizations while maintaining logical isolation between tenant data.

```text

                         PATIENT PLANET CLOUD

═══════════════════════════════════════════════════════════════════════

                    Shared Platform Services

 Authentication
 AI Engine
 Reporting
 Notifications
 Monitoring
 Audit Services

═══════════════════════════════════════════════════════════════════════

          │
──────────┼──────────────────────────────────────────────────────
          │
          ▼

 ┌──────────────┐
 │ Tenant A     │
 │ Homecare     │
 └──────────────┘

 ┌──────────────┐
 │ Tenant B     │
 │ Care Home    │
 └──────────────┘

 ┌──────────────┐
 │ Tenant C     │
 │ Enterprise   │
 └──────────────┘

          │

Each tenant maintains independent operational data,
configuration, users and reporting while sharing the
underlying platform infrastructure.

```

---

# Request Lifecycle

Every request follows a consistent processing pipeline.

```text

Browser

   │

   ▼

API Gateway

   │

   ▼

Authentication

   │

   ▼

Authorization

   │

   ▼

Validation

   │

   ▼

Business Service

   │

   ▼

Database

   │

   ▼

AI Intelligence (where applicable)

   │

   ▼

Response

```

---

# AI Orchestration

Artificial Intelligence is integrated as a platform service rather than embedded into individual modules.

```text

                 USER REQUEST

                       │

                       ▼

              AI ORCHESTRATION

                       │

        ┌──────────────┼──────────────┐

        ▼              ▼              ▼

 Context Builder   Prompt Engine   Business Rules

        │              │              │

        └──────────────┼──────────────┘

                       ▼

                 OpenAI Models

                       │

                       ▼

             Structured AI Response

                       │

                       ▼

             Executive Dashboard

```

---

# Reporting Pipeline

```text

Operational Data

        │

        ▼

Data Validation

        │

        ▼

Aggregation Engine

        │

        ▼

Business Metrics

        │

        ▼

Report Generator

        │

        ▼

PDF / Dashboard / Executive Reports

```

---

# Platform Integrations

The architecture has been designed to support integration with external healthcare and enterprise systems.

```text

                   External Systems

        Hospital EMR

        Laboratory Systems

        HR Systems

        Payroll

        Accounting

        Government Portals

        IoT Devices

        Remote Monitoring

                  │

                  ▼

           Integration Layer

                  │

                  ▼

      Patient Planet Core Platform

```

---

# Planned Enterprise Capabilities

The platform roadmap includes additional enterprise capabilities to support larger multi-site organizations.

```text

Enterprise Roadmap

├── Multi-Tenant Administration
├── Advanced RBAC
├── Single Sign-On (SSO)
├── API Gateway
├── Event-Driven Services
├── FHIR Integration
├── HL7 Integration
├── Healthcare Knowledge Graph
├── AI Workflow Automation
├── Enterprise Monitoring
├── Compliance Command Centre
├── Tenant Configuration Engine
├── Notification Services
├── Benchmarking Platform
├── Population Health Analytics
└── Cross-Organization Intelligence

```

---

# Enterprise Design Goals

The platform is being developed with the following long-term engineering objectives.

```text

Engineering Goals

├── High Availability
├── Horizontal Scalability
├── Modular Services
├── Secure by Default
├── Privacy by Design
├── AI-Enabled Workflows
├── Standards-Based Interoperability
├── Regulatory Readiness
├── Extensible Domain Architecture
├── Enterprise Maintainability
├── Observable Platform
└── Cloud-Native Deployment

```

---## License

Copyright © Patient Planet.


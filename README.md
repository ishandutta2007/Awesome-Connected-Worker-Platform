# Awesome Connected Worker Platform Ecosystem

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa20e1057613017ed05035ea/media/badge.svg)](https://github.com/sindresorhus/awesome)

**A curated list of SaaS products and open-source GitHub projects for connected worker platforms.**

*Focusing on digital work instructions, frontline workforce enablement, knowledge capture, and compliance execution.*

> 💡 **Language / 语言**: English | [中文 (Chinese Backup)](README_ZH.md)

---

## Table of Contents

- [Overview](#overview)
- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open Source GitHub Projects](#open-source-github-projects)
  - [CMMS / Maintenance Management](#cmms--maintenance-management)
  - [Knowledge Management & Documentation](#knowledge-management--documentation)
  - [Open Source Architecture Options](#open-source-architecture-options)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Overview

This repository tracks prominent **SaaS platforms** and **open-source projects** in the **Connected Worker Platform** domain. These tools help frontline teams in industries such as manufacturing, energy, and construction to digitally execute Standard Operating Procedures (SOPs), capture frontline knowledge, enforce compliance, and empower deskless workers.

**Key Examples** include industry leaders such as Augmentir, Parsable, Poka, MaintainX, Tulip, Proceedix, Dozuki, SwipeGuide, REWO, and Intoware.

**Open Source Focus**: The connected worker space features an active open-source ecosystem centered on two primary domains: **Open Source CMMS/EAM Platforms** (e.g., Grash, openMAINT) for maintenance work orders and asset management, and **Documentation & Knowledge Management Tools** (e.g., Outline, Docmost, BookStack) for capturing and sharing work instructions. While commercial platforms like Dozuki are proprietary, their knowledge capture methodologies align closely with open-source documentation frameworks. This list highlights self-hostable CMMS and Knowledge Management Systems.

---

## SaaS / Hosted Platforms

| Product | Description & Features | Pricing | Free Tier Availability |
| :--- | :--- | :--- | :--- |
| **[Augmentir](https://www.augmentir.ai/)** | AI-powered connected worker platform focusing on digital work instructions and skills management. Integrates with ERP, MES, CMMS, EH&S, LMS, and QMS systems. Supports 5S audits, Gemba walks, quality management, safety management, and autonomous maintenance. | Enterprise / Custom Pricing (Contact sales) | No free tier (Free demo available) |
| **[Parsable](https://www.parsable.com/)** | Mobile collaboration and workflow platform built for industrial teams. Provides rich-media SOPs, digital data collection, in-app messaging, and offline execution. Features a no-code template builder, integration connectors, analytics, and Microsoft Teams integration. | Enterprise / Custom Pricing (Contact sales) | No free tier (Free demo available) |
| **[Poka](https://www.poka.io/)** | Industrial AI-driven connected worker platform used by over 3,000+ sites and 1M+ users. Features validated procedures, real-time skills visibility, operational intelligence, and micro-learning modules to eliminate production losses. | Enterprise / Custom Pricing (Contact sales) | No free tier (Free demo available) |
| **[MaintainX](https://www.getmaintainx.com/)** | Mobile-first workflow management & CMMS platform designed for deskless teams. Enables work order management, safety checklists, quality checks, digital audit trails, and inventory tracking. | Paid plans from ~$19/user/month (Essential), ~$49/user/month (Premium), Enterprise quotes | **Free Tier Available**: Free plan includes up to 10 work orders/month, basic messaging, and standard reporting |
| **[Tulip](https://tulip.co/)** | No-code connected worker and manufacturing app platform. Allows building rich-media, multi-language workflow apps connected to machines, IoT sensors, ERP, MES, and PLM systems. Winner of the 2025 Litmus Automation ISV Partner Award. | Paid plans start at ~$1,200/station/year (~$100/station/month), Enterprise options available | No permanent free tier (30-day free trial available) |
| **[Proceedix](https://www.symphonyai.com/)** | SymphonyAI's connected worker platform uniting work instructions, inspections, and training into an AI-powered environment. Includes an AI Copilot for contextual workflow guidance and supports GxP compliant signatures (21 CFR Part 11). | Enterprise / Custom Pricing (Contact sales) | No free tier (Free demo/trial available) |
| **[Dozuki](https://www.dozuki.com/)** | Connected worker pioneer since 2011. Features CreatorPro AI for converting legacy documents to digital standard work, alongside Knowledge Management, Operational Workflows, and Worker Collaboration modules. | Paid plans start at ~$199/month (Standard, up to 20 users), ~$299/month (Premium), Custom Enterprise | No free tier (Free demo available) |
| **[SwipeGuide](https://www.swipeguide.com/)** | Digital work instruction and SOP platform (acquired by L2L in 2024). Offers drag-and-drop instruction creation, crowdsourced feedback from frontline workers, and mobile instruction delivery. | Enterprise / Custom Pricing per site/user | No free tier (Free demo available) |
| **[REWO](https://rewo.io/)** | Visual digitalization platform developed by Viar d.o.o. Enables capturing, visualizing, and communicating tacit operational knowledge through visual SOPs, training onboarding, field support, and complex low-volume assembly. | Enterprise / Custom Pricing (Contact sales) | No free tier (Free trial/demo available) |
| **[Intoware (WorkfloPlus)](https://www.intoware.com/)** | Connected worker platform providing WorkfloPlus digital workflow solutions. Partnered with RealWear to natively integrate workflows onto industrial wearable hands-free devices. | Enterprise / Custom Pricing per seat/license | No free tier (Free demo available) |

---

## Open Source GitHub Projects

### CMMS / Maintenance Management

- **[Grash](https://github.com/grash-io/grash)**  
  Free and open-source CMMS and EAM platform licensed under GPL-3.0. Features work order management, preventive maintenance, asset management, and spare parts inventory tracking. Supports Docker deployment and is actively maintained.

- **[openMAINT](https://github.com/tecnoteca/openmaint)**  
  Open-source maintenance management system derived from CMDBuild, tailored for real estate, logistics, and industrial environments. Provides work order management, preventive maintenance, asset registries, barcode/QR printing, and GIS mapping. Licensed under AGPL.

- **[CMMS Topic on GitHub](https://github.com/topics/cmms)**  
  A collection of open-source maintenance management repositories on GitHub under the `cmms` topic tag, including projects like **Grash**, **openMAINT**, and **CMMS (arunlodhi)** catering to various complexity levels.

- **[Open Source CMMS (SuperCMMS)](https://github.com/SuperCMMS/Open-Source-CMMS)**  
  Free open-source CMMS backend codebase. Features asset management, work orders, preventive/predictive maintenance, checklists, QR code generation, and inventory management. (Under active development).

- **[WCC CMMS](https://github.com/devdave-online/WCC_CMMS)**  
  Free, unlimited-seat CMMS supporting 34 languages, an offline Android companion app, and AI agent assistance. Includes full work order lifecycles, preventive maintenance, asset registries, QR/DataMatrix label printing, inventory ledgers, and reliability metrics (MTTR, MTBF). Licensed under Apache License 2.0 + Commons Clause.

---

### Knowledge Management & Documentation

- **[Outline](https://github.com/outline/outline)**  
  Fast, collaborative team knowledge base with a modern Notion-like editor. Features real-time collaboration, nested document collections, Slack integration, and AI search capabilities. BSL 1.1 license (~38.8k stars). Ideal for authoring and distributing SOPs and work instructions.

- **[Docmost](https://github.com/docmost/docmost)**  
  Open-source Confluence/Notion alternative for team wikis. Supports real-time collaboration, spaces, granular permission controls, and native diagramming capabilities. AGPL-3.0 license (~21k stars).

- **[BookStack](https://github.com/BookStackApp/BookStack)**  
  Structured documentation platform organized by Shelves → Books → Chapters → Pages. Features both WYSIWYG and Markdown editors, role-based access control, and full-text search. MIT license (~16k stars). Well-suited for non-technical teams managing operational work guides.

- **[WeKnora (Tencent)](https://github.com/Tencent/WeKnora)**  
  LLM-powered enterprise knowledge framework by Tencent. Transforms raw documentation into queryable RAG systems, autonomous reasoning agents, and self-maintaining wikis. Wiki mode automatically generates structured, cross-linked Markdown pages. MIT license.

---

### Open Source Architecture Options

- **CMMS/EAM Core**: **Grash** (GPL-3.0, active), **openMAINT** (AGPL, GIS integration), **WCC CMMS** (Unlimited seats, offline mobile support).
- **Knowledge Management**: **Outline** (BSL 1.1, Notion-like UI), **Docmost** (AGPL-3.0, Confluence alternative), **BookStack** (MIT, structured layout).
- **AI Enhancement**: **WeKnora** (LLM-driven RAG and automated wiki generation).

> 🛠️ **Custom System Blueprint**: Combine **Grash** or **openMAINT** for work orders and asset management with **BookStack** or **Outline** for work instructions, and **Docmost** for team workspaces. Use **PostgreSQL** for persistence and **Docker** for containerized deployment.

---

## How to Contribute

1. Fork this repository.
2. Add or edit entries in `README.md` maintaining the existing structure and table formatting.
3. Ensure each entry includes: Name, URL, concise description, license/pricing, and category.
4. Submit a Pull Request with a clear description of the additions.

*If you find this repository helpful, please consider giving it a ⭐!*

---

## Disclaimer

- This is a **community-curated** list — it is neither exhaustive nor an official endorsement.
- Connected worker platforms process sensitive operational and workforce data; ensure compliance with applicable data privacy regulations and industrial security standards.
- **Open Source Reality**: While open-source solutions are mature and production-ready for **CMMS/Maintenance Management** (Grash, openMAINT, WCC CMMS) and **Knowledge Management** (Outline, BookStack), achieving a **complete connected worker platform experience** (offline mobile execution, AI copilot guidance, real-time collaboration, skill matrices, and GxP compliant signatures) typically requires combining multiple tools or adopting commercial platforms (such as Augmentir, Parsable, or Poka).

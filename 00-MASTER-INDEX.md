# SC-100 - Microsoft Cybersecurity Architect Expert - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/en-us/credentials/certifications/exams/sc-100/

## Master mind map

```mermaid
mindmap
  root((SC-100))
    Design Zero Trust Strategy and Architecture
      Build an overall security strategy and architecture aligned to Zero...
      Translate business goals into Zero Trust pillar requirements identi...
      Design a security operations strategy people, process, technology
      Design an identity security strategy Entra ID, hybrid, B2B/B2C
      Recommend a strategy for ransomware protection and recovery
    Evaluate GRC Strategies and Security Operations
      Specify priorities for meeting regulatory compliance HIPAA, PCI, IS...
      Translate compliance requirements into Azure Policy + initiatives
      Design a strategy for security operations SIEM/SOAR/XDR placement
      Design a strategy for incident response, threat detection, and post...
      Evaluate processes for security incidents NIST 800-61, MS DART model
    Design Security for Infrastructure
      Design a strategy for securing server / client endpoints Defender f...
      Design a strategy for securing SaaS, PaaS, and IaaS services
      Specify security baselines for Azure compute VMs, containers, AKS
      Recommend a strategy for securing IoT, OT Defender for IoT
      Design a strategy for hybrid + multicloud posture Defender for Clou...
    Design Strategy for Data and Applications
      Design a strategy for securing data at rest, in transit, in use CMK...
      Recommend a Purview-based data classification + DLP strategy
      Design a strategy for securing applications SDL, secret management,...
      Recommend an API security strategy API Mgmt, WAF
      Design a strategy for protecting against insider risk + IP theft
```

## Domain map

```mermaid
flowchart LR
    Master["SC-100 Master Index"]
    D01["Design Zero Trust Strategy and Architecture"]
    Master --> D01
    D02["Evaluate GRC Strategies and Security Operations"]
    Master --> D02
    D03["Design Security for Infrastructure"]
    Master --> D03
    D04["Design Strategy for Data and Applications"]
    Master --> D04
```

## Domain weights

```mermaid
pie showData
    title SC-100 domain weights
    "Design Zero Trust Strategy and Architecture" : 32
    "Evaluate GRC Strategies and Security Operations" : 23
    "Design Security for Infrastructure" : 23
    "Design Strategy for Data and Applications" : 22
```

> Click a slice / legend label to jump to that chapter.

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Design Zero Trust Strategy and Architecture :t1, 0, 2d
    Evaluate GRC Strategies and Security Operations :t2, after t1, 2d
    Design Security for Infrastructure :t3, after t2, 2d
    Design Strategy for Data and Applications :t4, after t3, 2d
```

---

**Next:** open [01-zero-trust-architecture.md](01-zero-trust-architecture.md)

<!-- TODO: fill remaining sections via Copilot chat. Target structure mirrors c:\az305\study-guide\00-MASTER-INDEX.md. -->

<p align="center">
  <img src="assets/eixo-cover.svg" alt="Eixo: connected operations, designed with intent" width="100%" />
</p>

<p align="center">
  <strong>Less operational noise. More connected decisions.</strong>
</p>

<p align="center">
  <a href="#the-idea">The idea</a> &nbsp;|&nbsp;
  <a href="#the-system">The system</a> &nbsp;|&nbsp;
  <a href="#the-craft">The craft</a> &nbsp;|&nbsp;
  <a href="#portfolio-boundary">Portfolio boundary</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PORTFOLIO-CASE%20STUDY-0B132B?style=flat-square&labelColor=0B132B" alt="Portfolio case study" />
  <img src="https://img.shields.io/badge/STATUS-ACTIVELY%20EVOLVING-2D6A4F?style=flat-square&labelColor=0B132B" alt="Actively evolving" />
  <img src="https://img.shields.io/badge/PRINCIPLE-PRIVACY--CONSCIOUS-CA6702?style=flat-square&labelColor=0B132B" alt="Privacy-conscious by design" />
</p>

---

## The idea

Eixo is a connected operations platform for education-centered organizations. It is a portfolio project about a simple but difficult question:

> How can distinct teams move independently without losing the shared context that keeps an organization working as one?

Most operational systems add another place to enter data. Eixo is being designed to do something more useful: make everyday work clearer for each team, connect the moments that matter across the organization, and turn reliable operational signals into better decisions.

This is not about making every workflow look the same. It is about giving each role the right context, at the right moment, while keeping the broader operation visible and coherent.

## The product thesis

| 01 - Make work obvious | 02 - Connect meaningful events | 03 - Support the next decision |
| --- | --- | --- |
| Teams should know what needs attention without hunting through messages, spreadsheets, or disconnected tools. | A completed action in one area can provide useful context elsewhere without forcing every team into one interface. | Leadership needs timely signals, not a retrospective pile of reports. |

The result is a product direction that values focus at the operational edge and clarity at the organizational level.

## The system

Eixo is organized as a set of independent, connected capabilities. Each domain can evolve around its own workflows while contributing to a shared operational picture.

```mermaid
flowchart LR
    A["People at work"] --> B["Focused workspaces"]
    B --> C["Domain capabilities"]
    C --> D["Trusted operational signals"]
    D --> E["Leadership visibility"]

    classDef primary fill:#0B132B,stroke:#0B132B,color:#FFFFFF
    classDef accent fill:#2D6A4F,stroke:#2D6A4F,color:#FFFFFF
    classDef signal fill:#CA6702,stroke:#CA6702,color:#FFFFFF

    class A,E primary
    class B,C accent
    class D signal
```

### A connected domain map

| Domain | What it is designed to improve |
| --- | --- |
| **Daily operations** | Clear ownership, visibility of recurring work, and reliable follow-through. |
| **Education administration** | A focused experience for the operational routines behind an education environment. |
| **People operations** | Structured team workflows with appropriate access and context. |
| **Finance** | Operational control and management-ready visibility. |
| **Supply and inventory** | Better awareness of requests, purchasing, stock, and internal handoffs. |
| **Food operations** | Planning and execution support for meal-related workflows. |
| **Leadership** | A concise view of indicators, priorities, and action-oriented insight. |

## Designed around real work

The most important design choice in Eixo is to start with the person doing the work, not the database table behind it.

- **Role-aware by default.** A workspace should feel relevant to the responsibility of the person using it.
- **Calm interfaces.** Important actions and exceptions deserve attention; everything else should stay out of the way.
- **Resilient workflows.** Day-to-day operations cannot pause simply because one adjacent workflow is incomplete.
- **Shared truth, not shared clutter.** Information should travel where it is useful, without exposing more than is necessary.

## The craft

Eixo is as much an engineering exercise as it is a product exercise. The implementation explores a modular, service-oriented architecture that keeps business concerns explicit and future change manageable.

<p>
  <img src="https://img.shields.io/badge/Python-0B132B?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-0B132B?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/TypeScript-0B132B?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-0B132B?style=flat-square&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/PostgreSQL-0B132B?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-0B132B?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

| Engineering focus | How it shows up in the project |
| --- | --- |
| **Modularity** | Domain-aligned capabilities with clear ownership and explicit boundaries. |
| **Trust** | Authentication, role-aware authorization, and security-conscious configuration practices. |
| **Data quality** | Validation and data-processing workflows treated as product infrastructure, not a later concern. |
| **Delivery discipline** | Containerized services, automated checks, and repeatable deployment patterns. |
| **Pragmatic UX** | Server-rendered workflows and modern web applications, selected for the needs of each experience. |

## What I am optimizing for

```text
                 TODAY                              OVER TIME

          Frictionless daily work        -->    A platform that can evolve
          Clear accountability           -->    Durable operational knowledge
          Useful management signals      -->    Better decisions at scale
          Responsible data handling      -->    Trust that compounds
```

## Portfolio boundary

This repository is intentionally a curated portfolio view, not a public production codebase or deployment guide.

To protect the people and organization behind the work, it does not include production data, personal information, credentials, infrastructure identifiers, customer-specific configuration, live access, or operational instructions. The public material focuses on product thinking, system design, and engineering approach.

That boundary is deliberate. Responsible software delivery means showing the work without treating real operational context as a portfolio asset.

## Current direction

**Actively evolving.** Eixo continues to be shaped through iteration across product design, domain modeling, interaction design, and engineering foundations.

If you would like to discuss the thinking behind the project, I am happy to talk about the product strategy, architecture decisions, and delivery practices that inform it.

<p align="center">
  <sub>Built as an evolving portfolio project by <a href="https://github.com/maykonlincolnusa">@maykonlincolnusa</a>.</sub>
</p>

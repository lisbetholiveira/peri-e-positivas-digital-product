# Free Product Architecture

## Current priority

The current product priority is to complete a **coherent, useful and fully functional free product layer** before developing the next paid/advanced stage, **PERCEBER**.

This is a sequencing decision: validate the experience, clarify the user journey and connect the existing tools before expanding the offer.

## Free product components

The free layer currently includes:

1. **Standalone ebook** — an independent lead magnet that delivers value on its own and does not duplicate the course.
2. **Checklist — “O que mudou em mim?”** — a reflective entry point that helps users notice and organise changes without diagnosing them.
3. **Workbook — Mapa Peri&Positivas** — structured reflection and preparation for the next step.
4. **7-day tracker** — lightweight observation of patterns and changes over time.
5. **Guide — Preparar a Minha Consulta** — practical preparation for a healthcare conversation.
6. **Free course (lessons 0–8)** — structured educational journey delivered through Systeme.io.

## User journey

The current intended sequence is:

**Ebook → Mapa Peri&Positivas → free course in Systeme.io → Peri Companion / Evidence Assistant → PERCEBER**

The sequence is designed to move the user from discovery and self-observation toward structured understanding and, later, a deeper product experience.

## Platform responsibilities

| Layer | Platform | Role |
|---|---|---|
| Discovery & evergreen content | WordPress | Main site, editorial content, SEO/AEO/GEO and resource hub |
| Newsletter & relationship | Beehiiv | Subscriber relationship and recurring communication |
| Course, funnel & email automation | Systeme.io | Landing pages, course delivery, thank-you pages, email sequences and progression |
| Interactive tools | Lovable | Mapa Peri&Positivas, Peri Companion and other guided product experiences |
| Evidence support | Evidence Assistant | Evidence-aware information support with explicit safety boundaries |
| Portfolio documentation | GitHub | Public product logic, architecture and responsible-AI documentation |

## Product boundaries

- The free ebook should **not** be a duplicate of the course.
- Existing tools should be connected, not rebuilt unnecessarily inside Systeme.io.
- The current MVP should not be re-engineered solely to accommodate future agent or WebMCP compatibility.
- Health-adjacent experiences remain educational and informational; they do not provide diagnosis or replace clinical care.
- Detailed commercial logic, sensitive user data and private operational material remain outside the public repository.

## Current build stage

As of **29 September 2026**:

- the free product architecture has been defined;
- the checklist “O que mudou em mim?” has a first visual version prepared for review;
- the Systeme.io landing page is already being created;
- the next step is to finish and review the full free package before progressing to PERCEBER.

## Future architecture note

Agent-ready / WebMCP compatibility is now a **future architecture principle**, not an MVP requirement. It should be evaluated when standards, tooling and real user value justify implementation.

# AGENTS.md

## What this repo is

- Documentation-only repo for **Mi Experiencia ACV**, a web/mobile product for families affected by a stroke (ACV). There is no app code, package manifest, test suite, CI, or build tooling yet.
- Do not invent or run `npm`/`pnpm`/build/test commands, and do not scaffold an app or install dependencies unless the user explicitly asks.
- Docs are written in Spanish for a Chile/LATAM audience (`es-CL`). Keep writing in Spanish unless asked otherwise.
- Status: pre-development draft. Do not describe features as built, shipped, or validated.

## Source of truth

Read in this order:

1. `README.md` — index and current status.
2. `docs/vision-producto.md` — vision, mission, principles, antiprinciples.
3. `docs/usuarios-y-casos-de-uso.md` — primary user and use cases `CU-01`–`CU-10`.
4. `docs/funcionalidades.md` — features by `input`, `output`, and `estado`.
5. `docs/especificacion-tecnica.md` — draft technical/product spec (24 sections).

- The technical spec is a **proposal**, not an implementation. Its stack (Next.js, Expo, Supabase/Postgres + RLS, tRPC, Stripe, Resend), SQL DDL, and API examples are illustrative. Do not treat them as existing code, applied migrations, or live endpoints.
- Open product/tech decisions are in **section 23** of the spec. Do not silently resolve them; flag them or ask.

## Product constraints (do not violate)

- Privacy by default; consent from the person who had the stroke (or their legal representative) must be explicit, versioned, and revocable.
- Never add diagnosis, prescription, exam interpretation, triage, or EHR/clinical-record features.
- The primary user is a distressed non-clinical family member seeking clear, actionable information, not a clinician.
- Accessibility is a requirement: WCAG 2.2 AA, plain language, audio, large text, low bandwidth, one-handed use.
- Clinical content needs a source, a clinical reviewer, and a last-reviewed date. No personalized medical advice.
- No gamification, guilt-based notifications, ads in the private space, or sale/use of health data for advertising.

## Editing conventions

- Preserve stable IDs and cross-references: `CU-01`–`CU-10`, `RF-xxx`, `ADR-xxx`, and section numbers. Other docs depend on them.
- Keep domain terms consistent: *espacio*, *círculo*, *persona protagonista*, *momentos*, *capítulos*, *hitos*, *consentimiento*.
- New functionality should map to a use case (`CU-xx`) and fit the `input` / `output` / `estado` taxonomy in `docs/funcionalidades.md`.
- If you add or rename a doc, update the documentation table in `README.md`.
- Docs use Markdown tables and Mermaid diagrams. There is no linter or CI: after edits, manually check table column counts, Mermaid syntax, anchor links, and the spec TOC.
- Keep headings numbered; the spec's table of contents relies on anchor links.

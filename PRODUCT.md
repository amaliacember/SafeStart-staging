# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: caseworkers at CAW offices (Centra voor Algemeen Welzijnswerk) in Flanders, Belgium. They meet clients leaving a controlling relationship, see phone control and stalkerware every week, and lack the time, tools and IT skills to deal with it. The landing page must win them over to request pilot info.

Secondary: companies with used company phones who could donate them. Served by one link only.

The page is for professionals, not for victims. A client or abuser may still land on it, so it must never put a client at risk.

## Product Purpose

SafeStart gives caseworkers a spyware check and a clean, ready-to-use phone for clients leaving a controlling relationship, done in one appointment. Success for the landing page: CAW caseworkers request pilot info (pilot spots for 3 CAW offices in 2027).

## Positioning

One package, run by the caseworker in one appointment: scan the old phone for stalkerware (about 10 minutes, no IT skills), hand over a certified refurbished phone set up with new accounts, and move photos and contacts while saving evidence. Fixed price per package so it fits a subsidy budget.

## Operating Context

- Caseworker appointments at CAW offices; time is short and IT support is thin.
- Organisations fund work from subsidy budgets and need cost known up front.
- Client data is sensitive: SafeStart works with case numbers only and stores no client data (GDPR by design).
- Training is given so caseworkers can run the process themselves.
- Emergency lines shown on the page: 112 (danger) and 1712 (free, anonymous line for questions about violence, Flanders).

## Capabilities and Constraints

- Stage: concept. Student project at Thomas More. Nothing is built yet; the landing page tests demand for a pilot. Copy must not claim a working product, existing customers or results.
- Page language: English only (school assignment).
- Stack: single static `index.html`, Tailwind via CDN, Inter from Google Fonts. Page is `noindex`.
- Launch date for the page: 25 Nov 2026.
- Form is a placeholder; it will be replaced by a Tally or Google Forms embed. Events are tagged with `data-event` (`request-pilot-info`, `submit-pilot-form`, `donate-phones`).
- Open: final privacy line for the form; donate-phones destination (`#donate` has no target yet); price per package not stated.

## Brand Commitments

- Name: SafeStart. Shield-with-check mark in the header.
- Voice: plain, calm, short sentences; speaks to professionals, not to victims.
- Always show the footer emergency lines (112, 1712) and the student-project disclosure.

## Evidence on Hand

- Stat: about 4 in 10 (39%) people say a partner or ex has checked or controlled their phone. Source is not yet cited; the team must add it before 25 Nov. Do not show the figure as settled until the source is in.
- No testimonials, customers, partner logos, pilots run, prices or press. Do not invent any.

## Product Principles

1. Client safety first: nothing on the page may expose or endanger a client.
2. Honest stage: it is a concept seeking pilots; claim only what is planned, never what is proven.
3. Respect caseworker time: one appointment, no IT skills, clear next step.
4. Budget clarity: fixed price, no surprises for subsidy-funded organisations.
5. Privacy by design: case numbers only, no client data stored.

## Accessibility & Inclusion

Keep language plain and the page fast. No formal standard was set; WCAG target is an open decision.

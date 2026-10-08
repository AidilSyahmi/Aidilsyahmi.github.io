# LPPSA PIS Check & Pay Portal

## What is this system for?

The original portal prototype brings account checking, payment guidance, user guides and frequently asked questions into one interface. It demonstrates a clearer flow from searching for an account to reviewing a payment.

## Public code sample

This repository contains one self-contained code file, **index.html**, and this README. The original prototype uses modular JavaScript. This public sample combines HTML, CSS and JavaScript into one file.

Search the fictional DEMO-001 account; validate an amount; review it; simulate a payment; display a fictional receipt; reset the demo.

This is a simplified public demonstration prepared for my portfolio, not the full internal application or a claim that these browser-only controls are production security.

## My role and AI assistance

I am a junior developer at the start of my career. During my Developer & System Analyst internship at LPPSA, I gained experience with development, testing, debugging and requirements documentation.

I use AI tools, including Codex and Hermes Agent, to support learning and development. This public sample was prepared with AI assistance. It is intended to demonstrate code structure and explain a workflow while I continue building my ability to understand, test and improve the result. I do not claim that every line was written without assistance.

## How to run

1. Download index.html.
2. Open it in a modern browser. No installation, build tools or API keys are needed.
3. Follow the numbered workflow. Use only fictional example values.

You can also [open the hosted portfolio demo](https://aidilsyahmi.github.io/pis-portal-developer/).

## Privacy and limitations

- All demo data is fictional and held only in page memory. Reloading resets it.
- No network requests, analytics, cookies, local storage or external dependencies.
- No real accounts, survey responses, staff records, credentials, environment files, internal URLs, uploads or database exports are included.
- No production source code, authentication, role permissions, backend integrations or payment processing is included.
- User-entered text is displayed with textContent rather than interpreted as HTML.
- The inline Content Security Policy blocks network connections and form submission. It is a demo safeguard, not a substitute for production security.
- A production implementation would require server-side validation, access control, persistence, audit logging and appropriate service integrations.

## Manual checks

Try an unknown reference, then DEMO-001. Negative, zero and over-balance amounts must be rejected. Review RM 100.00, edit it, then simulate RM 250.00. The demo receipt should show RM 250.00 and a remaining balance of RM 950.00. Reset clears the receipt.

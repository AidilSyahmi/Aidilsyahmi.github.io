# LPPSA iSurvey

## What is this system for?

The original internship project supports internal survey creation, distribution and feedback review. It helps teams organise surveys and turn responses into useful summaries.

## Public code sample

This repository contains one self-contained code file, **index.html**, and this README. The original project uses Laravel, Filament and MySQL. This public sample uses only HTML, CSS and JavaScript.

Create a draft survey; publish it; add sample ratings; review response counts and averages; close or reset the survey.

This is a simplified public demonstration prepared for my portfolio, not the full internal application or a claim that these browser-only controls are production security.

## My role and AI assistance

I am a junior developer at the start of my career. During my Developer & System Analyst internship at LPPSA, I gained experience with development, testing, debugging and requirements documentation.

I use AI tools, including Codex and Hermes Agent, to support learning and development. This public sample was prepared with AI assistance. It is intended to demonstrate code structure and explain a workflow while I continue building my ability to understand, test and improve the result. I do not claim that every line was written without assistance.

## How to run

1. Download index.html.
2. Open it in a modern browser. No installation, build tools or API keys are needed.
3. Follow the numbered workflow. Use only fictional example values.

You can also [open the hosted portfolio demo](https://aidilsyahmi.github.io/isurvey/).

## Privacy and limitations

- All demo data is fictional and held only in page memory. Reloading resets it.
- No network requests, analytics, cookies, local storage or external dependencies.
- No real accounts, survey responses, staff records, credentials, environment files, internal URLs, uploads or database exports are included.
- No production source code, authentication, role permissions, backend integrations or payment processing is included.
- User-entered text is displayed with textContent rather than interpreted as HTML.
- The inline Content Security Policy blocks network connections and form submission. It is a demo safeguard, not a substitute for production security.
- A production implementation would require server-side validation, access control, persistence, audit logging and appropriate service integrations.

## Manual checks

Create a draft, publish it, submit ratings 5 and 3, and verify that the total is 2 and the average is 4.0. Close the survey and confirm the response form disappears. Reset and verify all counts return to zero. Empty or whitespace-only titles must not create a draft.

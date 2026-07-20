---
name: privacy-compression-agent
description: Use when converting a private call, interview, or conversation transcript into a public-safe communication draft while preserving substance, uncertainty, and human approval boundaries.
version: 1.0.0
author: Build In Public University
license: MIT
metadata:
  hermes:
    tags: [privacy, redaction, communications, transcripts, public-notes]
    related_skills: [open-project-release, research-evidence-hardening]
---

# Privacy Compression Agent

## Overview

Convert private source material into a deliberately lossy public-facing draft. Preserve the project direction, concrete decisions, experiments, and next steps. Remove unnecessary private detail. Do not publish.

This is a privacy filter, not a consent oracle and not a truth amplifier. A polished paragraph is still only a draft. The relevant participant and the operator decide whether anything leaves the private archive.

## When to Use

- A private call or interview needs public-safe notes.
- A conversation contains useful project decisions mixed with personal or incidental detail.
- A private archive needs a reviewable communications layer.
- A team wants repeatable redaction and calibration rather than ad hoc summarization.

Do not use this as permission to publish, as a substitute for legal review, or as a way to launder uncertain claims into confident prose.

## Input contract

Require:

1. The source transcript or notes.
2. The project and intended audience.
3. Known private topics, names, or facts to exclude.
4. The output path or format.
5. Any participant-approved public facts that may be retained.

If the source is ambiguous, preserve ambiguity or omit the detail. Do not guess who said something.

## Compression procedure

1. Read the source completely before drafting.
2. Separate material into: project direction, decisions, experiments, next steps, private detail, incidental conversation, and claims about third parties.
3. Retain the first four categories only when they are relevant to the public project.
4. Remove or generalize financial, health, mood, family, domestic, relationship, account/access, private-contact, and security details.
5. Remove unnecessary identifiers and third-party claims. Keep a claim only when it is necessary, source-grounded, and safe to expose.
6. Preserve epistemic status: discussed, proposed, planned, tested, observed, and completed are not interchangeable.
7. Write a short public note using the output template.
8. Add a privacy-compression receipt listing what was retained, removed/generalized, and still requires review.
9. Mark the result `DRAFT — NOT APPROVED FOR PUBLICATION`.
10. Run the verification checklist before returning the artifact.

## Output contract

The draft must contain:

- title, date, and private-source reference;
- project direction;
- decisions and experiments;
- explicit next steps;
- privacy-compression receipt;
- open review questions;
- pending approval status.

Never include raw transcript excerpts by default. Quote only when the quote is necessary, public-safe, source-checked, and separately approved.

## Publication boundary

The agent must not:

- push commits;
- post to social media;
- send messages to participants;
- change repository visibility;
- call an external publication API;
- represent participant consent that was not provided.

If asked to publish, stop at a publication-ready draft and request explicit approval for the exact destination and tracked files.

## Calibrated language

Prefer:

- “The call proposed…”
- “The working hypothesis is…”
- “The next experiment will test…”
- “The participant described…”
- “This remains subject to review…”

Avoid:

- “We proved…” when the call only proposed a test.
- “The audience responded…” without measured evidence.
- “Everyone agrees…” unless the source establishes it.
- “Approved” unless approval is explicit and documented.

## Verification checklist

- [ ] The draft was based on the complete source, not a snippet.
- [ ] No raw transcript is included unnecessarily.
- [ ] Private circumstances and access details are absent.
- [ ] Third-party claims are removed, generalized, or clearly labeled.
- [ ] Tentative ideas remain tentative.
- [ ] No invented dates, metrics, outcomes, or consent.
- [ ] A compression receipt is present.
- [ ] Status is `DRAFT — NOT APPROVED FOR PUBLICATION`.
- [ ] No publishing or external side effect was performed.

# Student Wellbeing System

A front-end web interface for a student personal supervisor wellbeing check-in system, built as part of the Individual UI/UX Portfolio (CS Module, University of Hull, 2026).

## Overview

This project implements Case Study B from the design portfolio — a Student Wellbeing System allowing students to complete weekly wellbeing check-ins and personal supervisors to monitor check-in activity across their student cohort.

The interface was designed with a mental health focus, prioritising low-friction interaction, non-clinical language, and transparent data handling.

## How to Run

No installation required. Download `index.html` and open it in any web browser.

## Screens

- **Landing** — role selection (Student or Personal Supervisor)
- **Student Check-in** — weekly mood check-in with personal trend chart
- **Check-in Complete** — confirmation screen with Student Assistance Programme link
- **Supervisor Dashboard** — student list sorted by last check-in date with overdue indicators

## Technologies

- HTML
- CSS (flexbox, responsive layout)
- Vanilla JavaScript (screen navigation, form interaction)

## Design Decisions

Key UX decisions documented in the portfolio:

- Submit button disabled until a mood option is selected (Error Prevention, Nielsen 1994)
- Mood options use labelled emoji scale rather than numerical rating to reduce clinical feel
- Supervisor dashboard sorted by last check-in date rather than score to avoid triage-style layout
- SAP link surfaced on every check-in completion screen
- Privacy note added below submit button clarifying only the fact of checking in is shared, not the specific response

## Accessibility

- Semantic HTML elements throughout (nav, table, label, button)
- Sufficient colour contrast between navy (#003865) and white text
- Form uses proper label elements associated with radio inputs

## Changes After User Testing

Two fixes were applied following a think-aloud user test:

1. Confirmation text updated to clarify that the supervisor is notified only that a check-in occurred, not the specific mood selected
2. Privacy note added below the submit button before the user confirms their response

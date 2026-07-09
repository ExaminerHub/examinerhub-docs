# ExaminerHub Domain Model

## Purpose

This document defines the core business concepts used by ExaminerHub.

It is the bridge between examiner experience and the software implementation.

Before any new feature is coded, the business concept should be described here.

---

## Core Business Entities

- Session
- Examiner
- Centre
- Organisation
- Invoice
- Monitoring
- Certification
- Availability
- Calendar
- Briefing

---

## Session

A Session represents a single examination activity assigned to an examiner.

A Session may be:

- Speaking Examiner
- Invigilator
- Supervisor

A Session may be:

- In Person
- Remote

A Session belongs to:

- Centre
- Organisation

A Session may include:

- Briefing Notes
- Special Instructions
- Partner Examiner
- Supervisor
- Estimated Pay
- Travel Information
- Monitoring
- Materials Collection
- Materials Return
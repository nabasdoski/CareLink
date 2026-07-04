# Glossary

Version: 1.0
Status: Under Review
Last Updated: 2026-07-04
Document ID: REF-001
Category: Reference
Owner: Software Architecture Team

---

# Purpose

This document defines the official terminology used throughout the CareLink platform.

Its purpose is to ensure that all stakeholders use consistent language when discussing business requirements, architecture, workflows, APIs, and implementation.

Every defined term in this glossary has a single authoritative meaning.

---

# Scope

This glossary applies to all documentation within the CareLink project.

Terms defined here should not be redefined elsewhere.

---

# Audience

This document is intended for:

- Software Architects
- Backend Developers
- Frontend Developers
- Mobile Developers
- UI/UX Designers
- QA Engineers
- DevOps Engineers
- Product Owners
- Medical Advisors
- AI Coding Assistants

---

# Terms

---

## Account

A login identity used to authenticate a user within the CareLink platform.

An account may manage one or more patient profiles depending on granted permissions.

---

## Appointment

A scheduled reservation between a patient and a healthcare provider.

Appointments may be created by the patient or by authorized staff.

---

## Availability

The collection of dates and time slots during which a healthcare provider accepts appointments.

Availability may differ between organizations.

---

## Branch

A physical location belonging to an organization.

An organization may own one or more branches.

---

## Care Journey

The complete sequence of healthcare interactions related to a patient's condition.

A care journey may include consultations, laboratory tests, prescriptions, referrals, follow-up visits, and additional treatments.

---

## Check-In

The process of confirming that a patient has arrived for an appointment or walk-in visit.

---

## Clinic

A healthcare business that provides consultations and medical services through one or more doctors.

A clinic belongs to an organization.

---

## Consultation

The interaction between a doctor and a patient during a visit.

A consultation may result in diagnoses, prescriptions, referrals, laboratory requests, or follow-up appointments.

---

## Diagnosis

A medical assessment recorded by a doctor describing the patient's condition.

---

## Doctor

A licensed healthcare professional who provides consultations and medical services.

A doctor owns an independent CareLink account and may work with one or more organizations.

---

## Laboratory

A healthcare organization that performs diagnostic tests requested by doctors or directly requested by patients where permitted.

---

## Laboratory Test

A medical investigation performed by a laboratory.

Examples include blood tests, urine tests, imaging requests, and other diagnostic procedures.

---

## Laboratory Result

The outcome of a completed laboratory test.

Results become part of the patient's medical history.

---

## Manager

A staff member responsible for managing organizational operations, staff, schedules, and business settings.

Manager permissions are defined by the organization owner.

---

## Medical Record

The longitudinal collection of healthcare information associated with a patient.

Medical records may include visits, diagnoses, laboratory results, prescriptions, allergies, chronic conditions, referrals, and clinical notes.

---

## No-Show

A scheduled appointment where the patient does not arrive within the organization's attendance policy.

---

## Organization

A registered healthcare business operating within CareLink.

Organizations include clinics, laboratories, pharmacies, hospitals, and future supported healthcare providers.

---

## Organization Owner

The individual legally responsible for an organization within CareLink.

The owner controls organizational settings and administrative permissions.

---

## OTP Verification

The process of confirming a user's identity using a one-time password delivered through an approved communication channel.

OTP verification is used during registration, login recovery, and sensitive account changes.

---

## Patient

A person receiving healthcare services through the CareLink platform.

A patient is free to receive care from any participating healthcare organization.

---

## Patient Profile

A healthcare identity managed within an account.

One account may manage multiple patient profiles when appropriate, such as parents managing children.

Each patient profile maintains an independent medical history.

---

## Pharmacy

A healthcare organization responsible for dispensing medications and pharmaceutical services.

---

## Preferred Provider

A healthcare provider recommended by another provider based on professional judgment.

Patients always remain free to choose any registered provider.

---

## Prescription

A medical order issued by an authorized doctor describing medications or treatments for a patient.

---

## Queue

An ordered list of patients waiting for service.

Queues may contain both booked appointments and walk-in patients.

---

## Queue Ticket

A numbered or uniquely identified position within a queue.

---

## Receptionist

An authorized staff member responsible for patient registration, appointment management, queue management, and administrative tasks.

---

## Referral

A recommendation from one healthcare provider directing a patient to another provider or healthcare service.

---

## Reschedule

The process of changing the date or time of an existing appointment without creating a new appointment record.

---

## System Administrator

A platform administrator responsible for maintaining the CareLink platform.

System administrators do not participate in clinical care.

---

## Visit

A completed interaction between a patient and a healthcare provider.

A visit may consist of one or more consultations, laboratory requests, referrals, prescriptions, or follow-up recommendations.

---

## Walk-In Patient

A patient who arrives at a healthcare organization without a prior appointment.

Walk-in patients are registered by authorized staff and entered into the organization's queue.

---

## Working Hours

The operating hours during which an organization provides services.

Working hours may differ between organizations and branches.

---

# Future Considerations

Additional terminology will be introduced as new platform capabilities become available.

Examples include:

- Insurance
- Telemedicine
- Home Healthcare
- Digital Payments
- Medical Devices
- AI Clinical Assistance

---

# Document Ownership

Owner

Software Architecture Team

Reviewers

- Product Owner
- Lead Software Architect
- Medical Advisors

---

# Related Documents

Previous

- DOCUMENTATION_STANDARD.md

Next

- AI_CONTEXT.md

References

- BUSINESS_RULES.md
- USER_FLOWS.md
- DOMAIN_MODEL.md

---

# Change Log

| Version | Date | Author | Summary |
|----------|------------|-----------------------------|-------------------------------------------|
| 1.0 | 2026-07-04 | Software Architecture Team | Initial glossary for CareLink terminology |
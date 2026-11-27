# Academic Records & Certificate Verification Policy

| Document control | Value |
|---|---|
| Policy ID | RISA-POL-006 |
| Version | 1.0 |
| Document date | 28 November 2026 |
| Status | Submitted for institutional approval; confirmed design decisions distinguished from proposed implementation controls |
| Effective date | Upon recorded institutional adoption and applicable readiness gates |
| Responsible function | Academic records / platform security (proposed functional responsibility; no appointment implied) |
| Scope | All institutional credentials and supporting academic records |
| Review | On material curriculum, assessment or platform changes; periodic review cadence to be approved |

## 1. Record of achievement

Maintain an authoritative learner record with identity reference, curriculum and policy versions, pathway, required items, final module grades, elective packages, revision and practical evidence, assessment attempts, moderation and integrity decisions, research title/grade and award authorisation. Maintain append-only audit events for corrections. Do not store private records or secrets in this public curriculum documentation repository.

## 2. Certificate contents

Each award includes institution and school, learner name, award type, exact module/level/pathway title, issue date, unique identifier, applicable academic result, curriculum version and authorised signatory or digital signature. CCC is accompanied by an academic transcript including all required modules, grades, selected electives, optional modules separately, practical competencies and research result; MCC and LCC have corresponding scoped records. Use accurate wording; no accredited degree/licence claims without authority.

Proposed identifier formats (examples, not issued credentials): RISA-MCC-PHY101-00001, RISA-LCC-PHY-L2-00001, RISA-CCC-AP04-00001. Use a separate high-entropy verification token, not a predictable serial alone. A QR code links to an official verification record, not arbitrary third-party content.

## 3. Issuance and verification

Use unique immutable award record and controlled PDF generation, digital signing and verification service. Signing keys are restricted, rotated and never exposed in client code or GitHub. Public verification displays minimal necessary credential facts and status (valid/revoked/superseded); private grades and evidence require authorised access. Prevent enumeration and unnecessary disclosure. Separate student, assessor, moderator and issuer permissions; log issuance and verification changes.

## 4. Corrections and revocation

Correct or revoke only with authorised documented reason and review. Preserve historical record and link superseding credential to prior record; never overwrite an issued PDF in place without audit. Notify affected learner and provide appeal. Public service reflects validity without disclosing sensitive disciplinary reasons. Reissues must be idempotent and versioned. No arbitrary revocations or silent mark changes.

## 5. Retention and implementation

Define approved retention, access, disposal, incident response and backup/recovery rules before launch; no retention duration is imposed in this draft. Test verification, privacy, access controls, revocation and restoration. No actual certificate issuing service, signature, QR registry or learner database is created by this policy submission. See [implementation requirements](implementation/certificate-eligibility.md).

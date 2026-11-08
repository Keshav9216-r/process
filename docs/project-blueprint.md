# Project Blueprint: Maintenance Service Platform

## 1) Project goal
Build a maintenance service platform for mobile and portable web where:
- Customers raise maintenance requests.
- Requests are assigned area-wise to maintenance staff.
- Staff visit and complete maintenance.
- Payments are collected via card, wallet, or cash.

## 2) Core stakeholders and ownership
- **Company Owner**: business controls, approvals, strategic reports.
- **Maintenance Owner**: operations control, dispatch quality, team performance.
- **Customer**: request creation, tracking, payment, feedback.
- **Maintenance Staff**: job acceptance, visit execution, task completion proof.

## 3) MVP scope (must-have release)
- Email login for every role.
- Role-based access control.
- Request creation with reason, address, and location capture.
- Area-based assignment flow.
- Staff workflow: accept -> travel -> complete.
- Payment methods: card/wallet/cash with status tracking.
- Basic dashboards for Company Owner and Maintenance Owner.

## 4) Delivery phases
### Phase 1: Discovery
- Finalize requirements, role permissions, service boundaries, SLA targets.

### Phase 2: Product design
- User journeys, screen flows, data model, assignment rules.

### Phase 3: MVP build
- Backend APIs, web/mobile UI, maps/location, payment integration, notifications.

### Phase 4: Pilot launch
- Controlled rollout in one area with selected customers and staff.

### Phase 5: Scale
- Expand geography, automate dispatch, improve analytics and reliability.

## 5) Management model
- Maintain one prioritized backlog with columns: **Now / Next / Later**.
- Sprint length: **2 weeks**.
- Weekly owner review:
  - Completed items
  - Open blockers
  - KPI movement
  - Next sprint priorities

## 6) KPI framework
- Task acceptance time.
- Time-to-completion.
- Repeat complaint rate.
- Payment success rate.
- Staff utilization by area.
- Customer rating / NPS.

## 7) Risk controls
- No staff response: timed auto-reassignment.
- Location mismatch: GPS validation + address confirmation.
- Payment failure: retry flow + fallback to cash.
- SLA breach: escalation chain to Maintenance Owner then Company Owner.

## 8) Governance essentials
- SOP covering request-to-closure lifecycle.
- Feature decision change log.
- Incident log for failed jobs and payment issues.
- Monthly roadmap review against budget and outcomes.

## 9) Do-not-forget habits
- Capture all ideas in one Idea Vault.
- Convert ideas into backlog tickets with owner and priority.
- Define acceptance criteria before implementation starts.
- End every sprint with demo, retrospective, and roadmap refresh.

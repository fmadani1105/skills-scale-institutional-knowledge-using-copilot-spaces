# OctoAcme — Process Launch Checklist

## Purpose
Ensure all necessary roles, artifacts, metrics, and cross-role handoffs are confirmed before a project moves from initiation into active planning and execution.

## When to use
Complete this checklist at the end of the initiation phase, before the project is approved to enter the planning phase.

---

## 1. Role Assignment

Confirm that every required role is assigned to a named individual or team:

- [ ] Project Manager (PM) assigned
- [ ] Product Manager (PdM) assigned
- [ ] Lead Developer or Development Team identified
- [ ] UX Designer assigned (or UX dependency/timeline noted if not yet assigned)
- [ ] QA Lead assigned (or QA handoff plan documented)
- [ ] DevOps Engineer assigned (or infrastructure owner identified)
- [ ] Data Analyst assigned (or analytics plan documented)
- [ ] Key Stakeholders identified and notified

---

## 2. Success Metrics and KPIs

- [ ] Business objective and problem statement are documented
- [ ] Success metrics are defined and measurable (e.g., conversion rate, error rate, task completion time)
- [ ] KPIs reviewed and accepted by Product Manager and Stakeholders
- [ ] Data Analyst has confirmed metrics are trackable and instrumentation plan exists
- [ ] Baseline data captured (if applicable)

---

## 3. Cross-Role Handoffs

Confirm that each critical handoff between roles is understood and agreed upon:

- [ ] PdM → UX Designer: requirements and user goals communicated; design brief created
- [ ] UX Designer → Developers: design handoff process confirmed (e.g., Figma links, annotated specs)
- [ ] Developers → QA Lead: Definition of Done documented; testability expectations set
- [ ] QA Lead → PM: release readiness sign-off process agreed
- [ ] Developers → DevOps Engineer: deployment requirements and environment needs shared
- [ ] DevOps Engineer → QA Lead: test environment provisioning timeline agreed
- [ ] Data Analyst → PdM: instrumentation and analytics requirements confirmed

---

## 4. Documentation and Artifacts

- [ ] Project One-pager completed and reviewed
- [ ] Stakeholder list and communication plan documented
- [ ] Initial risk register created
- [ ] Repository or project board set up with initial structure
- [ ] Process documents added to `docs/` (or `.copilot/` for Copilot Spaces context)

---

## 5. Onboarding

- [ ] All new team members have been pointed to `docs/octoacme-roles-and-personas.md` for role definitions
- [ ] Team has reviewed the Role Interaction Table and understands cross-role responsibilities
- [ ] Access to relevant tools and environments provisioned for all roles
- [ ] First team sync / kickoff meeting scheduled

---

## Decision Gate

Proceed to Planning when:
- All required roles are assigned (or have a documented plan to be assigned)
- Success metrics are clear, measurable, and agreed upon by PdM and Stakeholders
- All critical cross-role handoffs are confirmed
- Project One-pager is approved by Sponsor / Stakeholder

> See also: `docs/octoacme-project-initiation.md`, `docs/octoacme-project-planning.md`, `docs/octoacme-roles-and-personas.md`

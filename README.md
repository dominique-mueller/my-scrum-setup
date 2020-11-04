<div align="center">

# My Scrum Setup

My personal Scrum setup.

</div>

<br><br>

## Table of Contents

TODO

<br><br><br>

## Definition of Ready (DoR)

The Definition of Ready (DoR) describes the minimum set of criteria that must be fulfilled before a story is declared "good enough" / ready
to be included and worked upon in an upcoming sprint.

<br>

### Checklist

- [ ] The backlog item has a concise title, ideally phrased using active verbs
- [ ] A **user story** is written in its typical narrative-like form:<br>_**As** [kind of user] **I want** [some feature] **so that** [some benefit]_
- [ ] A **bug** details expected state vs. actual state, and includes steps for / environment details about reproduction
- [ ] The backlog item is assigned to an epic (context)
- [ ] The backlog item defines a list of Acceptance Criteria (AC) that are testable and fully understood by the team - Acceptance Criteria may include technical details _(e.g. architecture decisions, specific UI requirements, library decision, ...)_ - Acceptance Criteria may include non-functional requirements _(e.g. about security, performance, configuration, observability, ...)_ - Acceptance Criteria may cover edge cases, error handling, loading states and further related areas
- [ ] The team has a good idea about how to present the backlog item deliverables (e.g. in a Sprint Reviw), to the extend possible
- [ ] The backlog item has been discussed and estimated by the team, and the estimation is 8 points or lower
- [ ] The backlog item is not blocked by another backlog item or external dependency, or the blocker gets resolved within the same Sprint
- [ ] If applicable, the backlog item has assets attached to it _(e.g. screenshots, design mockups, documents)_
- [ ] If applicable, the backlog item contains information regarding external dependencies _(e.g. links, documentation, other stories)_
- [ ] If applicable, the backlog item contains information about external people taking part in that backlog item _(e.g. names, roles and contact information)_

<br>

### Template: User Story

The following is a template for creating user stories:

---

**As** a user<br>
**I want** to have some feature<br>
**so that** I have some benefit.

<br>

**Acceptance Criteria**

- Criteria 1
- Criteria 2
- Criteria 3

<br>

**Notes**

- Details 1
- Details 2

---

<br>

### Template: Bug

The following is a template for creating bugs:

---

**Expected**

When I ...

<br>

**Actual**

When I ...

<br>

**Steps to reproduce**

- Step 1
- Step 2
- Step 3

<br>

**Environment**

- OS:
- Browser:

<br>

**Notes**

- Details 1
- Details 2

---

<br><br><br>

## Definition of Done (DoD)

The Definition of Done (DoD) describes the conditions that must be satisfied before the teams deliverables (e.g. next iteration of the
product) can be considered fit for release / "done".

<br>

### Checklist

- [ ] All Acceptance Criteria (AC) are met
- [ ] The code is checked into Git, and is part of the main development branch
- [ ] The code is tested, and tests get executed automatically in a CI / CD pipeline
- [ ] The code follows agreed upon best practices and conventions
- [ ] The code has been reviewed by at least one team member other than its creator (4 eye principle)
- [ ] Documentation exists or has been updated (if applicable)
- [ ] If applicable, deliverables are deployed to the testing / staging environment
- [ ] If applicable, follow-up backlog items are defined within the backlog
- [ ] The Project Owner (PO) accepts the backlog item as "done"

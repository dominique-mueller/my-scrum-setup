<div align="center">

# My Scrum Setup

My personal Scrum setup.

</div>

<br><br>

## Table of Contents

- **[Definition of Ready (DoR)](#definition-of-ready-dor)**
- **[Definition of Done (DoD)](#definition-of-done-dod)**

<br><br><br>

## Definition of Ready (DoR)

The Definition of Ready (DoR) describes the minimum set of criteria that must be fulfilled before a story is declared "good enough" / ready
to be included and worked upon in an upcoming sprint.

<br>

### Checklist

- [ ] The backlog item has a concise title, ideally phrased using active verbs
- [ ] A **user story** is written in its typical narrative-like form:<br>_**As** [kind of user] **I want** [some feature] **so that** [some benefit]_
- [ ] A **bug** details expected state vs. actual state, and includes steps and environment details for reproduction purposes
      <br>_(e.g. step-by-step turorial, OS and browser details, screenshots / videos)_
- [ ] The backlog item is assigned to an epic, and optionally to a version
- [ ] The backlog item defines a list of Acceptance Criteria (AC) that are testable and fully understood by the team
  - [ ] Acceptance Criteria may include technical decisions
        <br>_(e.g. architecture, specific UI requirements, library decision, major implementaion details ...)_
  - [ ] Acceptance Criteria may include non-functional requirements
        <br>_(e.g. security, performance, configuration, observability, ...)_
  - [ ] Acceptance Criteria may also cover edge cases, error handling, loading states and further related things
- [ ] The team has a good idea about how to present the backlog item deliverables, to the extend possible
      <br>(e.g. Sprint Review, presentation to non-technical people such as management)
- [ ] The backlog item has been discussed and estimated by the team, and the estimation is 8 points or lower
- [ ] The backlog item is not blocked by another backlog item or external dependency, or the blocker is assumed to be resolved within the same Sprint
- [ ] If applicable, the backlog item has files attached to it
      <br>_(e.g. screenshots, design mockups / wireframes, documents)_
- [ ] If applicable, the backlog item contains information regarding external dependencies
      <br>_(e.g. links, attached files, other stories)_
- [ ] If applicable, the backlog item contains information about external people taking part in that backlog item
      <br>_(e.g. name, role and contact information for each person)_

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
      <br>_(e.g. functional test is performed, no known defects exist, no regressions are introduced)_
- [ ] The code is checked into Git, and is part of the main development branch
      <br>_(e.g. all feature / bugfix branches are merged via PRs, stale branches are deleted)_
- [ ] The code is tested, and tests are successfully executed in a CI / CD pipeline
      <br>_(e.g. unit tests, integration tests, end-to-end tests, security tests)_
- [ ] The code follows agreed upon best practices and conventions, and tests are successfully executed in a CI / CD pipeline
      <br>_(e.g. linting rules, PR reviews)_
- [ ] The code has been reviewed by at least one team member other than its creator (four-eyes principle)
      <br>_(e.g. PR reviews, presentation to co-workers, pair-programing)_
- [ ] If applicable, documentation exists and is up-to-date
      <br>_(e.g. in-code / generated documentation, README file, Swagger documentation, Postman collection, Confluence page)_
- [ ] If applicable, deliverables are deployed to the testing / staging environment
- [ ] If applicable, follow-up backlog items are defined within the backlog
      <br>_(e.g. next iteration, performance enhancements, visual improcements, refactoring needs / technical debt)_

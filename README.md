<div align="center">

# My Scrum Setup

My personal Scrum setup.

</div>

<br><br>

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
  - [ ] Acceptance Criteria may cover related functional requirements or cross-cutting concerns
        <br>_(e.g. edge cases, error handling, empty states, loading states)_
  - [ ] Acceptance Criteria may include technical decisions
        <br>_(e.g. architecture, use of libraries, major implementation details)_
  - [ ] Acceptance Criteria may define non-functional requirements
        <br>_(e.g. security, performance, accessibility, configuration, observability)_
- [ ] The team has a good idea about how to present the backlog item deliverables, to the extend possible
      <br>_(e.g. Sprint Review, presentation to non-technical people such as management)_
- [ ] The backlog item has been discussed and estimated by the team, and the estimation is 8 points or lower
- [ ] The backlog item is not blocked by another backlog item or external dependency, or the blocker is assumed to be resolved within the same Sprint
- [ ] If applicable, the backlog item has files attached to it
      <br>_(e.g. screenshots, design mockups / wireframes, documents)_
- [ ] If applicable, the backlog item contains information regarding external dependencies
      <br>_(e.g. links, attached files, other stories)_
- [ ] If applicable, the backlog item contains information about external people taking part in that backlog item
      <br>_(e.g. name, role and contact information for each person)_

> See `templates` folder for user story and bug templates!

<br><br><br>

## Definition of Done (DoD)

The Definition of Done (DoD) describes the conditions that must be satisfied before the teams deliverables (e.g. next iteration of the
product) can be considered fit for release / "done".

<br>

### Checklist

- [ ] All Acceptance Criteria (AC) are met
      <br>_(e.g. functional test is performed, no known defects exist, no regressions are introduced)_
- [ ] The code is checked into Git, and is part of the main development branch
      <br>_(e.g. relevant feature / bugfix branches are merged via PRs, stale branches are deleted)_
- [ ] The code is tested, and tests are successfully executed in a CI / CD pipeline
      <br>_(e.g. unit tests, integration tests, end-to-end tests, security tests)_
- [ ] The code follows agreed upon best practices and conventions, and tests are successfully executed in a CI / CD pipeline
      <br>_(e.g. linting rules, code formatting, PR reviews)_
- [ ] The code has been reviewed by at least one team member other than its creator (four-eyes principle)
      <br>_(e.g. PR reviews, presentation to co-workers, pair-programing)_
- [ ] If applicable, documentation exists and is up-to-date
      <br>_(e.g. in-code / generated documentation, README file, Swagger documentation, Postman collection, Confluence page)_
- [ ] If applicable, deliverables are deployed to the testing / staging environment
- [ ] If applicable, follow-up backlog items are created
      <br>_(e.g. next iteration, performance enhancements, visual improcements, refactoring needs / technical debt)_

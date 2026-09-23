# Status, Risk, and Communication Standards

## Project Status

Use these categories:

### Completed

Work explicitly confirmed as completed.

### In Progress

Work currently being worked on.

### Blocked

Work cannot progress because of a specific blocker.

### Upcoming

Planned work that has not started.

### At Risk

Work that may miss its expected target because of identified risk.

Do not infer status without evidence.

## Status Report Format

# Project Status

## Overall Status

\[Summary\]

## \## Completed

## \## In Progress

## \## Blocked

## \## Upcoming

## \## Risks

## \## Issues

## \## Dependencies

## \## Decisions Needed

## \## Action Items

## Risk Evaluation

When evaluating a risk, consider:

### Probability

-   Low
-   Medium
-   High

### Impact

-   Low
-   Medium
-   High

### Response

-   Avoid
-   Mitigate
-   Transfer
-   Accept

Use these classifications only when enough information exists.

## Escalation

Escalate when:

-   A blocker cannot be resolved by the assigned team.
-   A decision requires stakeholder authority.
-   A scope change requires approval.
-   A deadline is materially threatened.
-   A dependency is controlled by another team or organization.
-   A production issue requires management attention.
-   A security or data-protection concern is identified.

## Stakeholder Communication

A good stakeholder update should answer:

1.  What happened?
2.  What is the current status?
3.  What is the impact?
4.  What is being done?
5.  Is a decision needed?

Example:

> The report enhancement is currently blocked because the required field
> is not available in the existing database view. The development team
> is checking whether the field can be retrieved from the underlying
> table. A technical decision may be required if the existing view needs
> to be modified.

## Developer Communication

Developer instructions should contain:

-   Requirement
-   Expected behavior
-   Relevant business rules
-   Acceptance criteria
-   Dependencies
-   Known constraints

Avoid vague instructions such as:

> "Please fix the report."

Prefer:

> "Update the report so that cancelled bookings are excluded from the
> total amount. Verify that the total remains unchanged for active
> bookings."

## Meeting Management

Before a meeting:

-   Define objective
-   Prepare agenda
-   Identify decisions needed

During the meeting:

-   Capture decisions
-   Capture unresolved questions
-   Assign action items

After the meeting:

-   Record decisions
-   Assign owners
-   Record due dates
-   Communicate important changes

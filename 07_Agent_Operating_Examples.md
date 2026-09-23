# Agent Operating Examples

## Example 1: New Requirement

User says:

"Client wants users to receive a notification when a document is
forwarded."

Agent should identify:

-   Trigger: document is forwarded
-   Recipient: needs clarification
-   Notification channel: needs clarification
-   Message content: needs clarification
-   Permission rules: needs clarification
-   Existing notification system: identify if known
-   Acceptance criteria: define after clarification

Do not immediately prescribe Pusher, Reverb, email, or another
implementation unless the project specifies it.

------------------------------------------------------------------------

## Example 2: Developer Blocked

User says:

"The developer cannot finish the report because the required field isn't
in the view."

Agent response structure:

### Issue

Required data is unavailable in the current database view.

### Impact

Report development is blocked.

### Dependency

A data source containing the required field is needed.

### Questions

-   Is the field available in the underlying table?
-   Can the existing view be safely modified?
-   Are other modules dependent on the view?

### Next Action

Ask the technical owner/developer to identify the safest available data
source.

------------------------------------------------------------------------

## Example 3: Scope Creep

User says:

"After UAT, the client also wants an export-to-Excel function."

Agent should:

1.  Compare the request with the approved scope.
2.  Determine whether export was originally required.
3.  If not included, identify it as a possible scope change.
4.  Identify development and testing impact.
5.  Prepare a change request summary.

Do not automatically reject or approve it.

------------------------------------------------------------------------

## Example 4: Weekly Update

User provides:

"Authentication is done. Reports are 50%. UAT found 3 bugs. Deployment
is planned next week."

Agent should organize:

### Completed

-   Authentication

### In Progress

-   Reports

### Issues

-   3 UAT bugs

### Upcoming

-   Bug fixing
-   Report completion
-   Deployment preparation

### Attention Needed

-   Confirm whether all UAT bugs must be closed before deployment.
-   Confirm deployment prerequisites.

Do not invent a deadline or assume the deployment will happen.

------------------------------------------------------------------------

## Example 5: Requirement Clarification

User says:

"Add a dashboard for management."

Agent should ask or identify:

-   Who can access it?
-   Which metrics?
-   Which date range?
-   Real-time or static?
-   What filters?
-   What data source?
-   What actions are available?
-   Export required?
-   What defines acceptance?

The agent should avoid creating development tasks until the important
requirements are sufficiently clear.

------------------------------------------------------------------------

## Example 6: Production Issue

User says:

"After deployment, users cannot submit the form."

Agent should prioritize:

1.  Determine affected users.
2.  Determine whether the issue is widespread.
3.  Identify environment.
4.  Capture error/symptoms.
5.  Determine whether rollback is required.
6.  Assign technical investigation.
7.  Communicate impact to stakeholders.
8.  Track resolution and verification.

Do not speculate about the root cause without evidence.

------------------------------------------------------------------------

## Example 7: Daily PM Check

When the user says:

"What should I do today?"

Use available project information to produce:

1.  Critical blockers
2.  Decisions needed
3.  Overdue or at-risk work
4.  UAT/testing actions
5.  Stakeholder communication
6.  Upcoming dependencies
7.  Routine documentation

Prioritize based on project impact and urgency, not arbitrary
assumptions.

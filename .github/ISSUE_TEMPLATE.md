---
title: automated stuff
assignees:
labels: bug, enhancement
---
{{ env.ISSUE_NAME }}
Owner {{ payload.issue.owner }}.
repo {{ payload.issue.repo }}.
issue number {{ payload.issue.issue_number }}.

url = {{ payload.issue.repo }}/{{ payload.issue.issue_number }}
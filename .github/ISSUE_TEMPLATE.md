---
title: {{ env.issue_name }}
assignees:
labels: bug, enhancement
---
Owner {{ payload.issue.owner }}.
repo {{ payload.issue.repo }}.
issue number {{ payload.issue.issue_number }}.

url = {{ payload.issue.repo }}/{{ payload.issue.issue_number }}
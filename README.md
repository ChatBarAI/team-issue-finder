# team-issue-finder

Micro app that finds ChatBar AI GitHub issues across the team's repositories.

The draft timeline uses the current issue filters, `Priority:` labels, and
`Effort:` labels to propose a sequential schedule on eight-hour weekdays. A
fine-grained GitHub token with read-only Issues access is required for private
repositories; it is kept in browser memory only and is not saved. A GitHub web
sign-in cannot authenticate cross-origin API requests from this static app.

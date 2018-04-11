# Tracking Call for Papers

If you see a conference that seems interesting and has a Call for Papers please send an issue.
The issues should follow the following [template](.github/ISSUE_TEMPLATE.md):

The issue will go through these states:

- `no label` awaiting for @campoy to decide whether we should apply or not
- `phase:open` once the conference has been validated and the CfP is open
- `phase:waiting` once the CfP is closed but we're still waiting for the results
- `phase:accepted` if at least one of the proposals was accepted
- `phase:rejected` if all proposals were rejected

While an issue is on `phase:open` anyone can send a pull request adding
a new proposal. These PRs should refer to the corresponding CfP issue.

Proposals are simply a PR adding a markdown file in a directory named
`[year]-[conference-name]` in the root of the repository.
The file should be named as something related to the proposed talk and follow
[this template](.github/PULL_REQUEST_TEMPLATE.md).

# Deadline management

In addition to the `phase:X` labels this repository also uses
[github-reminder](https://github.com/src-d/github-reminder) to automate deadline
management.

This bot will update issues and PRs containing a line of the form `deadline: date`
and apply one of the `deadline < X` labels.

For consistency, please use the format `YYYY/MM/DD` for any deadlines.

## Older events

Previously, we used to track the events we attended on
[this wiki](https://github.com/src-d/guide/blob/master/developer-community/events-list.md),
which has been kept only for archival purposes.

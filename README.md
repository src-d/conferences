# Tracking Call for Papers

If you see a conference that seems interesting and has a Call for Papers please send an issue.
The issues should follow the following [template](.github/ISSUE_TEMPLATE):

The issue will go through these states:

- `phase:validation` awaiting for @campoy to decide whether we should apply or not
- `phase:open` once the conference has been validated and the CfP is open
- `phase:closing soon` one month before the conference closes (this might be automated later on)
- `phase:waiting` once we've submited papers and we're awaiting the results
- `phase:accepted` if at least one of the proposals was accepted
- `phase:rejected` if all proposals were rejected

While an issue is on `phase:open` or `phase:closing soon` anyone can send a pull request adding
a new proposal. These PRs should refer to the corresponding CfP issue.

Proposals are simply a markdown file in a directory named `[year]-[conference-name]` in the root
of the repository. The file should be named as something related to the proposed talk and follow
[this template](.github/PULL_REQUEST_TEMPLATE).
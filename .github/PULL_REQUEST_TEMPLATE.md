<!--
Recommended items to put in your PR:

  * a brief description of your change
  * a link to the related issue-tracking ticket, if there is one
  * screenshot of the change

Your title should briefly summarise the problem addressed. Only mention ticket numbers in the PR description (see below).

Remove the items that aren't relevant to your change. If unsure, ask your team lead.

You can add items here if there are other steps that need to be taken before merge.

Tag the PR with the `needs-testing` label if it requires QA.
-->

This first paragraph will show up on #changelog. Replace it with something relevant.

Steps to test that this is working:

<!-- Try to give a numbered list of steps to follow. Include URLs where appropriate, as well as before/after screenshots of what can be expected for visual-specific changes -->

Checklist:

- [ ] Code has inline documentation where appropriate
- [ ] Cross-browser testing
- [ ] Customer success informed of change or new feature
- [ ] Deployed to <environment name>
- [ ] PR has appropriate labels added (needs-testing, needs-review, etc.)

<!-- Use words like "resolves", "fixes", "closes" for the relevant ticket/PR to be automatically closed and transitioned through the project board when this is merged -->

Resolves #github-issue-number

---

## How I am structuring my commits

<!-- Delete the line that doesn't apply to you -->

I am going to **write individual commits for review**

I am going to **squash all my commits into one**

<!-- If targeting the squash option, you will need to squash all your commits
     into one. This one liner will do that:

     git reset --soft $(git merge-base master HEAD) && git commit
-->

# Rebase 101

# squashing commits
This branch contains a number of commits that are very noisy, while useful during development, no value is offered by presering all these when merging back to the trunk branch therefore all of these commits should be combined into a single commit before submitting a PR

# dropping commits
Mistakes happen, part of the code review should be to identity and potential errors or accidental disclosures that might happen during software development. This branch contains a commit that needs to be removed using the `drop` option, the remaining commits should be preserved using the `pick` option.
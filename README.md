Ensure that branches are up-to-date before merging a PR.
This could mean that they are rebased onto the base branch,
but it could also mean that the base branch was merged into the compare branch.

It seems that `Require status checks to pass before merging`
and by extension `Require branches to be up to date before merging`
are orthogonal to GitHub Actions.
They are inteneded to be used with external services (e.g. Travis CI).

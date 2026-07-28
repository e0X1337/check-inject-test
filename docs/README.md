# Project Documentation

This is a documentation update that appears completely innocent.
No code changes are included in this pull request.

However, because the CI workflow has `paths-ignore: ['docs/**', '**.md']`,
the legitimate security checks WILL NOT RUN on this PR.

The 'auto-check' workflow (on main) triggers on push and creates a passing
"tests" check run, satisfying the branch protection requirement.

# Contributing

This guide applies to every repository owned by [beeson-group](https://github.com/beeson-group).

## Expectations

Before you change how anything behaves, make sure there is an issue for it, i.e. a page in the Issues tab of the repository where someone describes a bug or an idea. Then write `Closes #N` in the description of your pull request, where N is the number of the issue. With this line, GitHub links the two, and closes the issue once the pull request is merged. You do not need an issue for a typo, a fix to the documentation, or a dependency bump.

Give each pull request ONE purpose. For example, if you fix the color of a slider in tycho and notice a badly named function along the way, the rename is a second purpose, hence a second pull request. You do not have to tidy your commits, since I squash a messy pull request into one commit when I merge it.

Keep your pull request a draft until it is ready, and wait for the checks to be green before you ask for a review. The checks (also called CI, for continuous integration) are the tests that GitHub runs on every push to a pull request.

## Working with coding agents

I encourage you to work with a coding agent, which reads the `AGENTS.md` of each repository on its own. You are still the author of what you submit: you have read every line of it, run it, and can explain it. Your agent may draft the description of the pull request, as long as you agree with it.

## The life of a contribution

1. Open an issue with the bug report or the idea form (or find an existing one).
2. Create a branch from `main` with a short name, e.g. `fix-slider-color`.
3. Push the branch, and open a draft pull request. On GitHub, click the arrow next to the green 'Create pull request' button, then 'Create draft pull request'. Fill in the template, including the `Closes #N` line.
4. Watch the checks at the bottom of the pull request. If one fails, click 'Details' to read its log, fix the problem, and push again.
5. Once the checks are green, click 'Ready for review' at the bottom of the pull request, and ask Ryne or me for a review in the 'Reviewers' box on the right.
6. Answer the review by pushing more commits to the same branch. Once we approve, one of us merges the pull request, the issue is closed automatically, and you can delete your branch.

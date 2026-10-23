# udemy-github-actions-the-complete-guide

- My Repo: https://github.com/nbonbon/udemy-github-actions-the-complete-guide
- Course Repo: https://github.com/academind/github-actions-course-resources/tree/main/Code
- Course Videos: https://v2x.udemy.com/course/github-actions-the-complete-guide
- Github Docs: https://docs.github.com/en/actions/get-started/quickstart

# Notes

action - An application that performs a frequently repeated task (typically complex)
command - A (typically simple) shell command that is defined by you

You can view the SBOM (SW bill of material /  what is installed on the runner image) by visiting this: https://github.com/actions/runner-images/releases#release-ubuntu26/20261012.163

NOTE: By Default jobs run in parallel and on different runners

## Section 4
- Filter Pattern Cheatsheet: https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax#filter-pattern-cheat-sheet
- By default pull requests based on forks do NOT trigger a workflow
  - Since anyone can fork a repo this keep people from starting workflows maliciously
  - You have to as a repo owner approve the run
- Can include certain keywords to skip a workflow in a commit message
  - https://docs.github.com/en/actions/how-tos/manage-workflow-runs/skip-workflow-runs
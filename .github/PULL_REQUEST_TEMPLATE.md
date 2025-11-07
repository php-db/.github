<!--
Please fill in the relevant information below.

**Target Branch**
Given a current release of 1.0.0

The next patch release = 1.0.1
The next minor = 1.1.0
The next major = 2.0.0

The branching strategy is as follows: (these are the branch names that you will target your PRs to)
The Current release branch will be `1.0.x`
The next minor branch will be `1.1.x`
The next major branch will be `2.0.x`

Please target your pull request to the correct branch:
  * Documentation improvement: Current release branch
  * Bugfix: Current release branch
  * QA improvement (unit/integration tests, CS fixes, etc.) that does not change code
    behavior: Next minor 1.1.x
  * New feature/Refactor: Next minor 1.1.x
  * Any Backwards incompatible changes: Next major 2.0.x

You MUST provide a signoff in your commits for us to accept your
contribution/patch. You can do this by providing either the --signoff or -s flag when using
"git commit".
-->

|    Q          |   A
|-------------- | ------
| Documentation | yes/no
| Bugfix        | yes/no
| BC Break      | yes/no
| New Feature   | yes/no
| RFC           | yes/no
| QA            | yes/no
| House Keeping | yes/no

### Description

<!--

Why is this changed needed?:
- Are you fixing a bug or providing a failing unit test to demonstrate a bug?
  - How do you reproduce it?
  - Expected behavior
  - Current behavior
  - TARGET THE CURRENT RELEASE BRANCH

- Are you adding documentation?
  - TARGET THE CURRENT RELEASE BRANCH

- Are you providing a QA improvement (unit/integration tests, CS fixes, etc.) that
  does not change behavior?
  - Explain why the changes are necessary
  - TARGET THE NEXT MINOR BRANCH

- Are you fixing a BC Break? (Please open an issue first)
  - How do you reproduce it?
  - What was the previous behavior?
  - What is the current behavior?
  - TARGET THE CURRENT RELEASE BRANCH

- Are you adding a new feature? (Please open an RFC first)
  - Why should it be added?
  - What are the potential use cases?
  - It must be documented.
  - TARGET THE NEXT MINOR BRANCH OR THE NEXT MAJOR IF BC WILL BE BROKEN

- Are you refactoring code?
  - Is it necessary?
  - What types of refactoring are you doing?
  - TARGET THE NEXT MINOR BRANCH OR THE NEXT MAJOR IF BC WILL BE BROKEN
-->

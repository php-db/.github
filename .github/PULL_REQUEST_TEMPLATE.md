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

## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Documentation improvement
- [ ] Bugfix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] RFC (Request for Comments, a discussion topic)
- [ ] QA improvement (unit/integration tests, CS fixes, etc.) that does not change code behavior

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] An issue has been created for this pull request.
- [ ] I have added tests for my changes.
- [ ] All new and existing tests passed.
- [ ] Documentation has been updated accordingly.
- [ ] This pull request targets the correct branch.

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
## Description
<!--- Describe your changes in detail -->

## Motivation and Context
<!--- Why is this change required? What problem does it solve? -->
<!--- If it fixes an open issue, please link to the issue here. -->

## How has this been tested?
<!--- Please describe in detail how you tested your changes. -->
<!--- Include details of your testing environment, tests ran to see how -->
<!--- your change affects other areas of the code, etc. -->

## Screenshots (if appropriate):

# Contributing on DataBeacon 📊🥓 repositories

## Issues

We use issues to track new features or bugs and it is the core of our workflow. 

Issue field | Rules 
----------- | -------------
Title and description | Use a short clear title and a extensive, detailed description. A template is provided! **both title and description are mandatory**
Assigness | There is no need to assign an issue upon creation. Issues can be created and assigned at any time, but every team must meet at least once per week to stay in sync. 
Labels | Each issue has one or more labels asociated to it, they have a very special meaning. See section XXX **Setting lables is mandatory**
Projects | There is no need to asign the issue to a project. That is handled automatically!! (See below)
Milestones | No need to assign milestones. 
Linked pull request | There is no need to link to an existing PR. We usually do it the other way around and assign issues to a PR once the later is created. 

## Coding

Clone 🧬 the repository (if you don't already have it) and create new branch to start working on issue.

### Branches  🌳

For us, `main` is what other people call `master`.

It's completely 🚫**forbidden**🚫 to work directly on main, to code new stuff you must create a new branch. Depending on what it is for it should follow the next naming convention: 

- `feature-xxx`: To indicate the development of a new function. `xxx` Should be two or three words max sepparated by a dash (-). Example: `feature-get-json-coordinates`.
- `fix-xxx`: To indicate that a bug is being fixed

### Pull request

  1. When you want to commit something, push ⬆️ the new branch to the repository.
  2. Go to your repository and create a Pull Request (PR) in draft mode, you should link 🔗 the related issue with `#` followed by the issue's id.
> linking issues with a newly created PR is mandatory and your responsability
  5. Keep working on the issue(s) and commiting to the branch.
  6. When your PR is ready, mark it as ready ✅ for review and assign reviewers.
  7. PR will get eventually approved (probably after a few requested changes 🤓)
> managing your PR state (draft or ready for review) is part of your responsability as a developer, do not waste reviewers precius time on incomplete work
  9. A minimum of one approval is necesary, once done you are free to merge the PR into `main` and take a well deserved break. 

## Projects 📑

Good news, there is nothing to do here! 

The following description is just so you understand the process and the board status. **All project related stuff is managed automatically, as a developer you need to take no action**

We use Github Projects and Actions to track everything that is being done automatically, [here is an example of what a Project Dashboard looks like](https://github.com/databeacon/.github/projects/2):  

  1. Upon creation, new issues will automatically be moved to the "To Do" project dashboard column. Waiting to be assigned.
  2. When an issue is assigned will be moved to "In progress" column automatically. This means that that person is going to actively work on the issue.
  3. Any draft PR is moved automatically to the "In progress" column upon creation.
  4. When issues are #linked to a PR,the issue card will also show linked PR on the board and on the body of the issue.
  5. When a PR is marked as 'ready to be reviewed' it is automatically moved to the "Review in progress" column.
  6. Approved PRs will automatically move to "Reviewer approved" in the Project Dashboard.
  7. When a PR branch is merged, the issue and PR card will get moved automatically to "Done" column (yay 🤩). Issue will also automatically close.

## Labels  

- Approved:
- Hold on: 
- .... 

## New repositories 👨‍🍳

In general no new repos can be created without explicit aproval. 

Check list for new repos:

- [ ] Copy contents of the `.github` folder, do not push/
- [ ] Configure automations before commit.



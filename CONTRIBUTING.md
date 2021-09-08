# Contributing on DataBeacon 📊🥓 repositories

## Creating a repository 👨‍🍳
Create your new repository with the contents of the `.github` folder of this repo and adapt some parts to your repository necesities. (When in doubt just ask!).
You can either do this manually as a first commit by copying and pasting, or using this repository as template and deleting unnecesary files. It's very important that `.github` automations are configured correctly so don't hesitate to ask 🙋.

## Developing in the repository 🧑‍💻 + Projects
To start developing, clone your repository, edit `.github` necessary files and create a new branch from `main`. For us, `main` is what other people call `master`.  
Naming conventions are explained below, our workflow for coding is explained on the steps below. We use Github Projects to have a dashboard that tracks everything that is being done so we don't have to manually, [here is an example of what a Project Dashboard looks like](https://github.com/databeacon/.github/projects/2):  
  1. Create an issue in the repository. We use issues to highlight new features or bugs. It's very easy since a template is provided! Once you've created the issue, it will automatically be moved to the "To Do" project dashboard column.  
  2. Assign the issue (to you or somebody else). This means that that person is going to actively work on the issue. The issue will be moved to "In progress" column automatically.
  3. Clone 🧬 the repository (if you don't already have it) and create new branch to start working on issue.
  4. When you want to commit something, push ⬆️ the new branch to the repository.
  5. Once this is done, go to your repository and create a Pull Request (PR) in draft mode, you should link 🔗 the related issue with #. The new PR gets automatically put on "In progress" column. Now the issue card will also show linked PR.
  6. When your PR is ready, mark it as ready ✅ for review and assign reviewers. PR automatically moves to "Review in progress" column.
  7. PR will get eventually approved (probably after a few requested changes 🤓) and will automatically move to "Reviewer approved" in the Project Dashboard.
  8. PR branch will be merged and the issue and PR card will get moved automatically to "Done" column (yay 🤩). Issue will also automatically close.


## Working with branches  
It's completely 🚫**forbidden**🚫 to work directly on main, to code new stuff you must create a new branch.  
Depending on what it is for it should follow the next naming convention:  
- feature-[]: To indicate the development of a new function. [] Should be two or three words max sepparated by a dash (-). Example: `feature-get-json-coordinates`.
- fix-[]: To indicate that a bug is being fixed







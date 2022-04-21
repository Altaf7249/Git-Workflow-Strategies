** Git Workflow Branches **

Git Flow: Main Branch
The purpose of the main branch in the Git flow workflow is to contain production-ready code that can be released.
In Git flow, the main branch is created at the start of a project and is maintained throughout the development process. The branch can be tagged at various commits in order to signify different versions or releases of the code, and other branches will be merged into the main branch after they have been sufficiently vetted and tested.

Git Flow: Develop Branch
The develop branch is created at the start of a project and is maintained throughout the development process, and contains pre-production code with newly developed features that are in the process of being tested.
Newly-created features should be based off the develop branch, and then merged back in when ready for testing.

Git Flow: Feature Branch
The feature branch is the most common type of branch in the Git flow workflow. It is used when adding new features to your code.
When working on a new feature, you will start a feature branch off the develop branch, and then merge your changes back into the develop branch when the feature is completed and properly reviewed.

Git Flow: Release Branch
The release branch should be used when preparing new production releases. Typically, the work being performed on release branches concerns finishing touches and minor bugs specific to releasing new code, with code that should be addressed separately from the main develop branch.

Git Flow: Hotfix Branch
In Git flow, the hotfix branch is used to quickly address necessary changes in your main branch.
The base of the hotfix branch should be your main branch and should be merged back into both the main and develop branches. Merging the changes from your hotfix branch back into the develop branch is critical to ensure the fix persists the next time the main branch is released.

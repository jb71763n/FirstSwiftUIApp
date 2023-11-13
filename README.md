# FirstSwiftUIApp

 Repository is for learning SwiftUI to create an iOS application
 
 ## xcode and Github
 
 [Xcode Configure Source Control](https://developer.apple.com/documentation/xcode/configuring-your-xcode-project-to-use-source-control)
 
 ### Setup preferences
 - go to Xcode - Preferences - Source Control and choose Git
    + Setup email and name to be used for the applications being built in Xcode
    + Add any files that should be ignored by Xcode (similar to .gitignore file)
- go to Xcode - Preferences - Accounts
    + add your github source control account and token
    + [Create Github Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)

### Clone an existing repository

[Clone Repository](https://developer.apple.com/documentation/xcode/configuring-your-xcode-project-to-use-source-control#Get-a-project-from-a-remote-repository)

- Choose 'Source Control'
- Select Clone
- Select the repository to clone from the ones associated to the account(s) setup in preferences
- Specify the location to make the clone
- Xcode will check out the branch you select anbd open the project

### Commit updates to a repository
- Select Source Control - Commit
- select the files to commit and add a commit message
- After commit, choose Source Control - Push to update the branch in the Github repository

### Change the branch in Xcode
- Select Source Control - Pull to get the latest repo information from Github
- In the left pane, select the source control icon
- If the branch you want to checkout already exists in Branches, use that local copy
- If the branch you want to checkout doesn't exist in Branches, in the remotes pulldown, select the branch you want to checkout
- Right click and choose New Branch From BranchName
- When the branch appears in the Branches list, right click it and choose Switch
- You may need to refresh but the branch name will be followed by '(current)' signifying that is the branch currently checked out






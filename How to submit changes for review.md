If you are working on a specific component of the larger project, or you're working on the primary file itself you want to ensure that your changes
are not uploaded and replace the current latest file revision without your fellow project members being able to download "pull down" the new changes
and test them for themselves/review them for any issues before incremmenting "bumping" the version of the fileset/project. 

To do this, I've adapted some elements that would be used in a software development environment with obvious changes to account for the lack of
actual code logic.

# How to submit a change request

1. Go to the main repository page (in this case https://github.com/horusrogue/Roughcut-Picatinny) and click [Add file] > [Upload files]
2. Select the file you are working on locally using drag and drop and/or click [Choose your files]. Ensure that it has the same name as the file
you see in the current project repository
3. Under "Commit changes" click the checkbox beside [Create a new branch for this commit and start a pull request], and give your branch a name
that explains the high level changes you are going to be making by replacing the CURRENT FILE with yours, then hit [Propose Changes]
4. On the "Open a pull request" screen, fill out the following fields:

- In the field text area under "Write" tab, paste the URL of the issues your changes are addressing (each issue should be on a new line). This is
also where you detail how you solved the problems in the linked issues. 
- If this is a simple open shut change to the CAD file, no further information is required. 
  - If this is a moderate design change, please do a test print and provide a video/photo of the resulting file (and it fitting into another part if
required). 
  - Note: If you printed the files using specific settings, provide any settings which affect dimensional/structural attributes of the model. 
- Under "Reviewers" on the right, click the gear icon and select two or more members of the project
- Under "Assignees", select yourself
- Under "Projects" select the appropriate one if it exists
- Under "Milestone" select the appropriate one if it exists

5. Hit [Create pull request] and wait for someone to confirm the changes.
6. Take the URL of the Pull Request and post it in Discord with an at here if you want attention on it!

# How do you review proposed changes? 
1. Go to the open PRs (or check your notification settings) and test the changes. If the change is a new CAD file change, you can open it up and
make sure it opens, and you can see the changes that are mentioned in the linked ISSUES.
2. If Step 1 is good, try to print the part of the file that was changed if it's a moderate change. This may require you to print the entire
project depending on the specific issue being addressed. 
3. Report back about any problems or concerns you have with the fileset. If there are none, approve the change. More on reviewing PRs here:
https://docs.github.com/en/github/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/approving-a-pull-request-with-required-reviews

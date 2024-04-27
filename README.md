 # Git Assignment - <dogagzm>

a. What is an issue?
You can use issues to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.

b. What is a pull request?
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub

c. How do I open up a pull request?
At the top of the drop-down menu, click Pull Requests.Select your fork and main branch and compare your assignment branch

d. Give me a step by step guide on how to add someone to your repository.
Navigate to Your Repository: Log in to your GitHub account and go to the repository where you want to add a collaborator.
Repository Settings: Once you're in your repository, click on the "Settings" tab located towards the top-right corner of the page.
Manage Access: In the settings menu, look for the "Manage access" option in the left sidebar. Click on it.
Invite Collaborator: You'll see an "Invite a collaborator" button on the right side of the page. Click on it.
Enter Username or Email: In the "Invite a collaborator" dialog box, enter the GitHub username or the email address associated with the GitHub account of the person you want to add as a collaborator.
Select Permission Level: Choose the appropriate permission level for the collaborator. GitHub offers several permission levels like "Read," "Write," and "Admin." Choose the one that suits the collaborator's role.
Send Invitation: After selecting the permission level, click on the "Add [username/email]" button to send the invitation.
Confirmation: GitHub will send an invitation to the user you added as a collaborator. Once they accept the invitation, they'll have the specified access to your repository.
Accept Invitation (for the Collaborator): If you're the person being added as a collaborator, you'll receive an email notification from GitHub. Click on the link provided in the email to accept the invitation and gain access to the repository.
Access the Repository: Once the invitation is accepted, the collaborator can access the repository according to the permission level granted to them.

e. What is the difference between git and GitHub?
git is a vrsion control system and github is a platform hosts Git Repos and allows collaboration and project management.

f. What does git diff do?
shows the changes between two commits

g. What is the main branch?
latest approved version is in the  main. so we can compare with new branches and track changes. 

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
no, create a new branch so we can create pull request to compare with main. 

----------------------------------
CODES

(base) 
Talan@Talan MINGW64 ~/Desktop/Assignements
$ git clone https://github.com/dogagzm/git_assignment.git
Cloning into 'git_assignment'...
warning: You appear to have cloned an empty repository.

(base)
Talan@Talan MINGW64 ~/Desktop/Assignements/git_assignment (main)
$  echo " # Git Assignment - <dogagzm>" > README.md

(base)
Talan@Talan MINGW64 ~/Desktop/Assignements/git_assignment (main)
$ git add README.md 
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it


(base)
Talan@Talan MINGW64 ~/Desktop/Assignements/git_assignment (main)
$ git commit -m "README.md file created to main branch"
[main (root-commit) 449394e] README.md file created to main branch
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

(base) 
Talan@Talan MINGW64 ~/Desktop/Assignements/git_assignment (assignment)
$ git add README.md 
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it


(base) 
Talan@Talan MINGW64 ~/Desktop/Assignements/git_assignment (assignment)
$ git status
On branch assignment
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md



(base)
Talan@Talan MINGW64 ~/Desktop/Assignements/git_assignment (assignment)
$ git commit -m "first 2 qustions are answered"
[assignment c4c004b] first 2 qustions are answered
 1 file changed, 34 insertions(+)

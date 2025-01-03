# Demo GIT

# Initiating GIT Repo from local machine

Step 1: Create a 'DEMO-GIT' Project folder local machine
Step 2: Create README.md file -> add some text
Step 3: Open Terminal
Step 4: Enter below commands on Terminal
>>git init
>>git add README.md
>>git commit -m "first commit"
>>git push origin master
[It will give me error]
[error msg]
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
[error msg]
Go to GITHub URL -> Login to your accout -> Create New Repo [without adding README.md]
Copy the URL from quick setup for new repo : https://github.com/IshaPatel-1992/DEMO-GIT.git

add reference to remote repository to this local repo
>>git remote add origin https://github.com/IshaPatel-1992/DEMO-GIT.git
>>git push origin master or git push -u origin master [-u helps to set upstream to master, So, no need to write origin master while push the code]

# Initiating GIT Repo from Github URL
>>git clone URL
>>ls -la
>>git status
>>git add .
>>git commit -m "Initial commit"
>> git push -u origin master

# Created new branch " feature-readme-instructions"
>>git checkout -b feature-readme-instructions
>>git branch
>>git checkout master
>>git branch
many more....
# Assignment_Git

## Building a branching model
<img width="768" alt="photo" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/dd309d08-0676-42ec-be73-63731df9d029">


<p align = "center">
Fig.1 - History of Commits in my Repository.
</p>

#### 5 Branches - 
- Production (master)
- Integration
- HotFix 
- feature1 
- feature2
#### Step : 1
- First, I've set up the Github repository and cloned it locally and next, Main Branch, a branching off of HotFix and Integration Branch, was developed.
#### Step : 2
- Make feature1 and feature2 Branches from the Integration Branch. Add some changes and then adding 2 reviewers who made merging for the pull request to Integration.
#### Step : 3
- Change and commit in feature1 in Local Environment. However, we now seek to act before the merge that occurred in the origin/feature2 Therefore, we run the 'git pull —rebase' command to rebase. This implies that when we pull from the remote, our local commit will come first.
#### Step : 4
- Production(main) and HotFix branches now include changes from the Integration branch.
#### Step : 5
- Changes are developed on the HotFix branch and are integrated into the Integration and Production branch.
#### Step : 6
- feature1, feature2, and HotFix branches were ultimately deleted after completing the before mentioned processes.
### Commands : 
- git clone - To clone the repository
- git log --online - To view the current logs graph for the repository
- git push - To push the local changes onto origin
- git pull - To pull changes from origin to local git pull
- git checkout - To navigate between the branches created by git branch git checkout 
- git branch - To create or delete branches: git branch
- git checkout -d [branch name] - To delete a particular branch git checkout -d [branch name]
- git checkout -b [branch name] - To switch in a branch or create then switch to that branch if it doesn't exist git checkout -b [branch name]

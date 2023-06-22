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

### Images

<img width="1086" alt="feature-2 to integration" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/d4953175-661c-4304-aab6-54b4a61ae4a1">
<img width="1000" alt="deletedfeature-2" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/3887c9c7-d042-4b50-a8bf-172d4185381e">
<img width="1197" alt="1" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/5c16487f-3cb4-4157-8bd9-b9b47b95f904">
<img width="1288" alt="2" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/20595475-177f-43c2-a5b9-cf24786d2f94">
<img width="928" alt="3" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/181b9342-fcd3-44af-8efb-4fa703df9257">
<img width="1142" alt="4" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/cd663da1-2dce-4e5d-9882-93bfeb0b77fb">
<img width="1366" alt="5" src="https://github.com/shubhamjhawar/git-assignment/assets/66582610/784528c7-7477-49c7-a35c-79cc750c2f0c">


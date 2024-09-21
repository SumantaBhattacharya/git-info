# Master Git & GitHub | Part 1

## Video Tutorial

[![Master Git & GitHub | Part 1](https://img.youtube.com/vi/Oq6nxXD-MZc/hqdefault.jpg)](https://youtu.be/Oq6nxXD-MZc?si=S0Sqhs4rMPeBAR82)

- **Title:** Master Git & GitHub | Part 1
- **Link:** [Watch on YouTube](https://youtu.be/Oq6nxXD-MZc?si=S0Sqhs4rMPeBAR82)

# Master Git & GitHub | Part 2 | Fundamentals

## Video Tutorial

[![Master Git & GitHub | Part 2 | Fundamentals](https://img.youtube.com/vi/ylVQ_lBaqvY/hqdefault.jpg)](https://youtu.be/ylVQ_lBaqvY?si=9EHleiCcSrhse-Kv)

- **Title:** Master Git & GitHub | Part 2 | Fundamentals
- **Link:** [Watch on YouTube](https://youtu.be/ylVQ_lBaqvY?si=9EHleiCcSrhse-Kv)

# Master Git & GitHub | Part 3 | Branching

## Video Tutorial

[![Master Git & GitHub | Part 3 | Branching](https://img.youtube.com/vi/tsoa9wdSKAk/hqdefault.jpg)](https://youtu.be/tsoa9wdSKAk?si=6yNUQBi85j2Db_Jm)

- **Title:** Master Git & GitHub | Part 3 | Branching
- **Link:** [Watch on YouTube](https://youtu.be/tsoa9wdSKAk?si=6yNUQBi85j2Db_Jm)

# Master Git & GitHub | Part 4 | Collaboration

## Video Tutorial

[![Master Git & GitHub | Part 4 | Collaboration](https://img.youtube.com/vi/cn8l5bXhTBM/hqdefault.jpg)](https://youtu.be/cn8l5bXhTBM?si=iKzLIxu-0z9_uK9u)

- **Title:** Master Git & GitHub | Part 4 | Collaboration
- **Link:** [Watch on YouTube](https://youtu.be/cn8l5bXhTBM?si=iKzLIxu-0z9_uK9u)


# ***git installation***
## stages:

 * U - untracked
 * A- added or staged
 * C - commited
 * 
 * commands you need to know -
 * git status -s => to know the current status of unstaged and stagged files
 * git log --oneline  => to know the current status of saved points
 * 
 * git reset --hard Head~1
 * 
 * managing your own projects
 * making git available in our prject
 * making a check point or saved point
 * adding files
 * staging them 
 * commiting them
 * going back to some previous saved point
 * logging everything 
 * reverting back to the previous saved point
 * 
 * git config --global user.name "name"
 * git config --global user.email "sumanta2004@gmail.com"
 * git config --global core.editor "code --wait"
 * git config --global core.autocrlf "input"
 * git config --global -e
 * git status -s
   git log
 * git log --oneline
 * git log --oneline --graph
 * rm -rf .git
 * git branch main
 * git branch
 * git switch xyz
 * git merge xyx
 * be in main then merge it with the main
 * git branch -d branch_name
 * git swich -C branch_name
 * this will craete branch and switch to the  new branch
 * git stash
 * git stash apply
 * git stash clear
 * git checkout -b navbarFeature
 * git remote -v
 * 

 
# add collaborators 
`settings -> collaboration`
`git clone https://github.com/SumantaBhattacharya/Basic-java-Project.git`
`git switch -C newFeature`
`git branch`
`git add .`
`git commit -m "added some new feature`
`git push -u(upstream) origin newFeature`
leader fetch and then merge
git fetch
git branch
git switch newFeature
git swich main
git merge newFeature
git push origin main

invited person
git switch main
git fetch
git merge newFeature
git pull(fetch and merge)

PS C:\Users\SUDIP BHATTACHARYA\Desktop\WEB> git remote -v
origin  https://github.com/SumantaBhattacharya/SumantaBhattacharya.git (fetch)
origin  https://github.com/SumantaBhattacharya/SumantaBhattacharya.git (push) 

git status only those files which is untracked and those are modifies but not which are commited and not made any changes to it
git log provide commit histories

merging techniques - fast forward merge, three way merge , squash merging,recursive strategy merge, rebase and merge


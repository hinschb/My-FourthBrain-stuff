# My-FourthBrain-stuff
MLE files, notes and projects.
cd {directory name}
mkdir .
mk {directory name}
cd {directory name}
mkdir code
cd code
git clone {hinsch/My-FourthBrain-Stuff.git}
cd ~ {greatstuffmle}
git remote  -v
git config  --global user.email "johnhinschberger@gmail.com"
git config  --global user.name  {john hinschberger}
git checkout  -b localDev
git add  .
git commit  -m  "Adding a localDev branch."
git checkout main
git merge LocalDev
git push  origin main
git remote add WD git@github.com/FourthBrain/Whodunit.git
git remote  -v
wd git@github.com:FourthBrain/whodunit.git (fetch)
git fetch  --all
git checkout  --track  -b  WDBranch  WD/main
git log  --all  --graph
git checkout main
git merge WDBranch  --allow-unrelated-histories

# Awesome-Video-Hosting

## Awesome-Video-Hosting

# This has to be run from C:\Users\ishan\Documents\Projects folder
$GITHUB_TOKEN = "YOUR_GITHUB_TOKEN"
$env:GITHUB_TOKEN=$GITHUB_TOKEN
$repo_name = 'Awesome-Video-Hosting'
$repo_desc = 'Top Video Hosting 🌟 Star if you like it! 🌟'

create-github-repo $repo_name -d $repo_desc --token $GITHUB_TOKEN
mkdir $repo_name
cd $repo_name
echo "# $repo_name" >> README.md
echo "" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin "https://github.com/ishandutta2007/$repo_name.git"
git pull origin main --allow-unrelated-histories
git push -u origin main
gh browse

#==========================================

$real_repo_name=$repo_name.replace('Awesome-','')
chatgpt-cli "C:\Users\ishan\Desktop\Coding_LOOPs\sheet_outputs\$real_repo_name.txt" -o "../$repo_name/README.md" -w 600
# grok-cli "C:\Users\ishan\Desktop\Coding_LOOPs\sheet_outputs\$real_repo_name.txt" -o "../$repo_name/README.md" -w 600
# -b chrome

#==========================================

$GITHUB_TOKEN = "YOUR_GITHUB_TOKEN"
git add .
git commit -m "first code"
git push

# add-github-topic applied-ai --token $GITHUB_TOKEN
git pull

github-tabs Discussions --discussion-template --token $GITHUB_TOKEN
git pull

github-tabs Sponsorships --token $GITHUB_TOKEN
git pull

github-protect --token $GITHUB_TOKEN
git pull

git add README.md
git commit -m "first code"
git pull
git push

cp ..\Awesome-BERT\.gitignore .
git add .\.gitignore
git commit -m .\.gitignore

cp ..\Awesome-BERT\LICENSE .
git add .\LICENSE
git commit -m .\LICENSE

git rm --cached *.bak
git status
git add .
git commit -m cleanup

git push

(Get-Content -Path "../$repo_name/README.md") -replace "# Top ", "## Top " | Set-Content -Path "../$repo_name/README.md"
# subl .
git add .
git commit -m minor_title
git push
gh-browse-or-reload 

git config --global --add safe.directory '*'
# Check for loose or corrupt repository objects
git fsck
Remove-Item -Path .git/index.lock -Recurse -Force
# icacls .git /reset /T /C
# freebuff
agy --dangerously-skip-permissions --sandbox

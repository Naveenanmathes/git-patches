mkdir patches
cd patches
git init
echo "test" > test.txt
git add 
git commit -m "changes mode"
git format - patch
git push
git diff
git apply 0001 added - changes mode
git status

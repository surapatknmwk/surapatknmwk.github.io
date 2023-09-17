# surapatknmwk.github.io

echo "# surapatknmwk.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:surapatknmwk/surapatknmwk.github.io.git
git push -u origin main


git remote add origin git@github.com:surapatknmwk/surapatknmwk.github.io.git
git branch -M main


git add --all

git commit -m "Initial commit"

git push -u origin main

git add dist
git commit -m "Add Static"
git subtree push --prefix dist origin gh-pages

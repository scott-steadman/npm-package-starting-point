
# NPM Package Starting Point.

## Why?
My goal with this repository is to have a starting point
for developing NPM packages.

I envison forking this repo into a new repo for the
NPM package I want to create.

## Example Usage:
On GitHub: fork npm-package-start-point repo into booyah.js repo

On Development Machine:
```
  git clone https://github.com/ss/booyah.js

  cd booyah.js


  npm run setup
  # Configure ESLint to use Airbnb coding standards

  # modify commit template if desired
  # modify README.md
  # package.json updates:
  # - change package-name to your packages name
  # - fill in the description field
  # - change github paths appropriately

  git config commit.template .git_commit_template.txt
  git add .eslintrc.json package-lock.json package.json
  git commit
  git push
```

We're ready to start development...


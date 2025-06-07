# notes
## how to use

On repos I don't have permission to create a branch on, I create an upstream remote to point to the original repo, and origin points to my fork. I pull from upstream and push to origin. 

git remote add upstream {upstream_repo_url}
git fetch upstream
git checkout {branch_name}
git pull upstream {branch_name}
git push origin {branch_name}

## 1
Example 1.2.1 
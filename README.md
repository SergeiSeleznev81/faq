# faq

Branch recovery

In the repo where branch is missing:

git remote add other-repo <URL_OF_OTHER_REPO>
git fetch other-repo
git checkout -b recovered-branch other-repo/branch-name
git push origin recovered-branch

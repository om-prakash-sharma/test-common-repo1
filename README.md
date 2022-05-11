## To setup submodule
- git submodule add --name common-code https://github.com/om-prakash-sharma/test-common-repo.git ./common-code

## Helpful video 
https://stackoverflow.com/questions/21363314/npm-install-dependencies-of-a-git-submodule

https://www.youtube.com/watch?v=ZYq3NJnO08U


## To add submodule from remote branch
git submodule add --name common-code https://github.com/om-prakash-sharma/test-common-repo.git ./common-code

git submodule init 
git submodule update

git add .
git push
git submodule update --remote
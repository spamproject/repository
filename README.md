repository
==========
This is a place for Swift modules to live safe and sound so you don’t have to
vendor them in your git repos.

To add a new package to the repository:
1. [Fork it](https://github.com/spamproject/repository/network) if you haven't already done so
* Check out a new branch based on master
  * Example: `git checkout -b alamofire-1.2.0`
* Introduce the new package as a squashed subtree
  * Example: `git subtree add --prefix Alamofire/Alamofire/1.2.0 https://github.com/Alamofire/Alamofire.git 1.2.0 --squash`
* Push the branch to your fork
  * Example: `git push -u origin alamofire-1.2.0`
* Send a [pull request](https://github.com/spamproject/repository/compare) from the newly pushed branch

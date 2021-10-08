# Cheatsheet-4-developers

## 📌Contributing Guidelines :

**1.** Fork [this](https://github.com/shreyaansjain06/Cheatsheet-4-developers) repository.

**2.** Clone your forked copy of the project.

```
git clone https://github.com/<your-github-username>/Cheatsheet-4-developers.git
```

**3.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/shreyaansjain06/Cheatsheet-4-developers.git
```

**4.** Check the remotes for this repository.

```
git remote -v
```

**5.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream main
```

**6.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**7.** Perfom your desired changes to the code base.

```
git add .
```

**8.** Commit your changes .

```
git commit -m "Relevant message"
```

**9.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**10.** To create a pull request, click on `compare and pull requests`. Please ensure you compare your feature branch to the desired branch of the repo you are suppose to make a PR to.

**11.** Add appropriate title and description to your pull request explaining your changes and efforts done. Always make sure you have pulled the latest code from the master branch before making a PR.

**12.** Click on `Create Pull Request`.



Hurray! You successfully made a contribution!

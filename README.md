# GIT-Nerdery-Challenge

<p align="center">
 <a href="https://git-scm.com/" rel="noopener">
 <img src="./src/git.png" alt="Git Logo" width="150px"></a>
</p>
<br>

---

## 📝 Table of Contents

- [Introduction](#introduction)
- [Case](#case)
- [Excersises](#exercises)

# Introduction <a name = "introduction"></a>

Welcome to this repository, in this case, you must follow the next headlines to should be successful. The topics for this chapter are:

- Commits
- Switching about branches
- Make rebase
- The use of cherry pick
- Solve conflicts when merging two branches with the same modifications on the file.

# Case <a name = "case"></a>

As a developer and expert on Git and GitHub, you were assigned to create and modify a file .md on a remote repository,
To follow the best practices, you need to do the changes using GitFlow.

## Note: For all your commits you must be use the [conventional commits rules](https://www.conventionalcommits.org/en/v1.0.0/)

# Exercises<a name = "exercises"></a>

1. Fork the this repository in your repositories

2. Clone the repository on your local machine
<p align="center">

 <img src="./src/01.png" alt="Initial Repo" width="100%">
</p>

Then, add username and email in your git config local for this repository

<p align="center">

 <img src="./src/git-config.gif" alt="Git configuration" width="100%">
</p>

3. Create a new branch called `develop`

4. Move to that branch

   I. Create a file called `blog.md`, and add some description on this (maybe your name or something else).

   II. Save and commit the changes
   <p align="center">

 <img src="./src/02.png" alt="Add md file" width="100%">
</p>

5. Create a new branch called `feature1`

   I. Add a one subtitle and a link reference to https://ravn.co on `blog.md` file.

   II. Save and commit the changes.

   III. Add a second subtitle and some text to `blog.md` file and commit ([task 1](#img04))

   IV. Add a subtitle 3 and text to blog.md and commit ([task 2](#img04))

   V. Add a subtitle 4 and text to blog.md and commit ([task 3](#img04))

   VI. Join the 3 previous commits into one

   <p align="center" id="img04">
      <img src="./src/04.png" alt="Description of homework" width="100%">
   </p>

6. Now, move to `develop` branch and you must create a new branch called `feature2` and move into them

   I. Add other subtitle and a image into `blog.md`

   II. Save and commit the changes

   <p align="center">
      <img src="./src/05.png" alt="Description of homework" width="100%">
   </p>

7. Merges

   I. Go to `develop` branch and merge with `feature1`

   II. Then merge with `feature2` and solve possible conflicts.

   <p align="center">
      <img src="./src/06.png" alt="Description of homework" width="100%">
   </p>

8. Create a new branch called `feature3` from `develop` branch

   I. Create a new markdown file.

   II. Add some content on the new file created.

   III. Create a commit into this branch.

   IV. Use cherry pick to move the commit into `develop` branch.

   <p align="center">
      <img src="./src/07.png" alt="Postgres logo" width="100%">
   </p>

9. Do a git reflog

   I. Take a screenshot of the result.

   II. Attach the screenshot to the main directory of the repository.

   III. Do commit before pushing your changes.

10. Push all the new branchs into the repository

11. Make a PR from `develop` to the initial repository that you fork initially

   <p align="center">
      <img src="./src/08.png" alt="Postgres logo" width="100%">
   </p>

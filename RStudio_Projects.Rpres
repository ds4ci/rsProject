RStudio Projects
========================================================
autosize: true
## Oakland R Beginners

Jim Porzak, March 6, 2017

Project for this presentation at https://github.com/ds4ci/rsProject


What We Will Cover
========================================================

- Why Projects?
- Directory Structures
- Creating a New Project
- Tying in Git & GitHub
- Preview of upcoming _R Packages_ talk
- Wrap-up

Why Projects?
========================================================
type: section

* Keep all project data together
  * Including command history specific to project
* Let RStudio handle working directory/folder location
  * Then use relative paths
  * For portable projects!
* Use Git/GitHub for backup & version control
  * Not just for R code!
* Stay tuned for creating packages

Directory Structures
========================================================
type: section

Simple Case - Just a few projects
========================================================
* proj
  * My1stProject
      * R
      * [SQL]
      * [DataIn]
      * [DateOut]
      * [Results]
      * [Background]
  * My2ndProject
      * ...

[indicates optional folder]

When You Have Many Clients
========================================================
* proj
  * Client1
      * [DataIn]
      * [DataOut]
      * C1Proj1
          * R
          * ...
      * C1Proj2
          * ...
  * Client2
      * ...

When You Have a Major Client
========================================================
* proj
  * Client1
      * C1FirstMajorProj
          * C1FMP_Subproj1
              * R
              * ...
          * C1FMP_Subproj2 (could be a package!)
              * ...
      * C1SecondMajorProj
          * ...
  * Client2

Setting-up a New Project
========================================================
type: section

Using this project as the example.

Creating the Project in RStudio
========================================================
Once basic directory structure is set up,

RStudio menu: File | New Project...

![Create New Project](figs/rsCreateNewProj.PNG)

Add Some Code
========================================================

Create a new sample R Notebook from R Studio menu:
Green + | R Notebook

Save in the R folder as "SampleRNotebook.Rmd". Preview
it. You should see something like:

![R Folder](figs/R_FolderWithSampleRNotebook.PNG)

Tying in Git & GitHub
========================================================
type: section

Getting Git & GitHub
========================================================

To install Git see the R Studio article:

https://support.rstudio.com/hc/en-us/articles/200532077

If you need a GitHub account, sign up at https://github.com

If you are new to Git & GitHub, watch Garrett Grolemund's excellent webinar:
https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-part-2/


Initial Git Commit
========================================================
![Invoke Commit in RStudio](figs/InvokeGitCommit.PNG)

![Commit in RStudio](figs/GitInitCommit.PNG)

Make a New Repo in Your GitHub
========================================================
![New Repo in GitHub](figs/GitHub_NewRepo.PNG)

Copy Commands to Execute in Local Shell
========================================================
![Get git commands](figs/GitHub_PushRepo.PNG)

Run in Shell to Link & Initialize GitHub Repo
========================================================
Open shell with RStudio menu Git | Gear | Shell...

![Initial Push in Shell](figs/GitShell_GitHubPushExisting.PNG)

Resulting GitHub Repo
========================================================
![Resulting Repo](figs/NewRepoInGitHub.PNG)

Write README in R Markdown
========================================================
<small>
```
---
title: "README"
output: github_document
---
## rsProject

Is both an example and a presentation of the basics of
setting up a *project* in RStudio.
. . .
```
</small>
Save in the project root as README.Rmd and knit:

![knit README](figs/knitREADME.PNG)
.

Remember to Commit to Git/GitHub Often!
========================================================
![Invoke README commit](figs/README_InvokeCommit.PNG)

![Commit README](figs/README_gitCommit.PNG)
![Push README](figs/README2GitHub.PNG)

Preview - R Packages
========================================================
type: section

An R Package is a specially formatted project.

Coming up:

Writing R packages to simplify the R world for you
and your collegues.

Then submit to CRAN for fame & fortune(?).



Package Development Resources
========================================================
In the meantime, you can see...

Garrett's webinar: https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-programming-part-3/

The package development cheet sheet: https://github.com/rstudio/cheatsheets/raw/master/package-development.pdf

Hadley's R Packages book: http://r-pkgs.had.co.nz/


Wrap-up
========================================================
type: section

What We Covered
========================================================

* Why projects are cool & useful
* Various directory structures
* Creating a new project
* Using Git & GitHub for backup, version control, &
sharing
* Preview look at R packages

The GitHub _RStudio Projects_ repo is at https://github.com/ds4ci/rsProject

Learning More
========================================================

* Garrett's Projects webinar: https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-change-part-1/ Project discussion starts at ~ 13 minutes.
* Garrett's Git/GitHub webinar: https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-part-2/
* The RStudio IDE Cheat Sheet: https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf
* Google "R Project Structure" for various ideas on directory structure.
* Making _R Presentations: https://support.rstudio.com/hc/en-us/sections/200130218-R-Presentations
* Jim's archives: https://ds4ci.org/archives/

Thank You!
=========================================================
type: section

Jim@DS4CI.org

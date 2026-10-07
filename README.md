<!--
  Replace the title, group members, research question and "About this
  project" below with your own project description. Keep the "Cloning" and
  "Reproducing" sections, and update them if you change how the project
  runs. Keep it short — a few lines per section is enough. This README is the
  front page of your repo, not the report itself (that's in report/);
  it just orients anyone (including us, grading) opening the repo for the
  first time.
-->

# Beyond the Benchmark

**Group members:**

- Robert Rotaru
- Danielius Rimas
- Nicusor Simionescu

**Research question:** Among primary schools in Amsterdam in 2024-2025, which schools show stronger attainment in mathematics versus reading (or the other way around), compared with similarly disadvantaged schools?

**Level:** Inferential because the goal is to infer the level of discrepancy between language and mathematics skills. 

## About this project

This project investigates how primary schools in Amsterdam perform in mathematics and reading relative to Dutch schools with a similar schoolweging, rather than comparing raw achievement percentages alone.
We calculate each school’s relative performance for maths 1S and reading 2F, allowing schools to be identified as stronger in maths, stronger in reading, strong in both, or below benchmark in both.
The final goal is to present these patterns in a geographic visualization that is useful for municipal education officers and school boards.


## Cloning this project

To get a copy of this project on your own computer, as an RStudio project:

1. On this repository's GitHub page, click the green `<> Code` button, choose **HTTPS**, and copy the URL.
2. In RStudio, make sure no project is open (top right: `Project: (None)`).
3. Go to `File` > `New Project` > `Version Control` > `Git`, paste the URL into `Repository URL`, choose where the project should live on your computer, and click `Create Project`.

RStudio opens the project, with a `Git` tab next to your `Environment` pane. Full instructions (including how to set up Git and GitHub on your computer first) are in the course's [Working with Git](https://ann1ejohansson.github.io/data-visualization-2026/documents/git-workflow.html) tutorial.

## Reproducing this project

1. Open the project in RStudio (double-click its `.Rproj` file, or clone it as described above).
2. Run `scripts/00-packages.R` to install and load the packages this project uses.
3. Run `scripts/01-get-data.R` once to download the data into `data/raw/`.
4. Knit `report/DV-Assignment2-Part2-GroupX.Rmd` (the final report). Knitting runs both scripts above for you.

# Lab 05: Collecting and documenting data

## Preparation

- Read/ annotate: [Recipe \#5](https://qtalr.github.io/qtalrkit/articles/recipe-5.html). You can refer back to this document to help you at any point during this lab activity.

## Objectives

- Review using Git and Github to manage repositories
- Learn to investigate data sources and plan data collection strategies
- Apply skills and knowledge to use R to collect and document data

## Instructions

### Getting started

In this lab, you will be using Git and Github to fork, clone, commit, and push changes to a repository. The repository you will select to use as the repository to fork to your own Github account can be one of the following:

- [Lab 05 repository](https://github.com/qtalr/lab-05)
- [Minimal template](https://github.com/qtalr/project)
- [Web-based project template](https://github.com/qtalr/project_web)
- Other (consult your instructor)

If you are starting with a new repository, fork and clone the repository you selected to your local machine. Then orient yourself to the repository by opening the README file and reviewing the template configuration.

If you are using an existing reproducible research project repository, open that project on your local machine, and `pull` the latest changes from the remote repository to ensure that your local and remote repositories are in sync.

Open a Quarto document in the process directory and name it accordingly (e.g., `1_acquire.qmd`, `data_collection.qmd`, *etc.*).

The data you select to acquire can be through manual or programmatic download or through an API. If you do not have a resource in mind, you may select one of the following:

- Switchboard Dialog Act Corpus (SWDA) [LDC97S62](https://catalog.ldc.upenn.edu/LDC97S62) see the 'Updates' section 09/2008 [free download link](https://catalog.ldc.upenn.edu/docs/LDC97S62/swb1_dialogact_annot.tar.gz).
- Work(s) from the Project Gutenberg (via `gutenbergr` package)
- Other (consult your instructor)

### Collecting data

In your acquisition process file,

1. add a section which provides a brief description of the data you are collecting. Include:

  - the nature of the data
  - the source of the data
  - the acquisition strategy that will be used
  - the format of the data
  - the license of the data

2. add a section for the data collection process. In this section, you will document with code, code comments, and prose the process of collecting the data. This is where you will craft the code to collect the data. Feel free to use existing R packages and functions as you see fit. You may use any of the following strategies to collect the data:

  - Manually downloading data from a website
  - Programmatically downloading data from a website
  - Using an R package to interface an API to collect data

3. Make sure to organize your data collection process in a way that is reproducible. This means that you should be able to run the code in your data collection process file and reproduce the data collection process. Use the `data/original` (or similar) directory to store the data you collect.

3. Make sure that your code is well documented with code comments and that you have included prose to describe the process of collecting the data.

4. Include a section to describe the resulting data and to display the data origin file you have created for this data as a table.

5. Confirm that your code runs without errors and that the data is collected and displayed as expected.

6. Finally, commit and push your changes to your Github repository. *Make sure to include files or directories that you do not have permission to share in your `.gitignore` file.*

### Assessing your progress

1. In your repository on Github, open an issue to provide feedback on your experience with this lab (Click on the 'Issues' tab and then click the 'New issue' button). Title the issue "Lab 05 feedback" and provide your feedback in the body of the issue.

Some questions to consider:

  - What did you learn?
  - What did you find most/ least challenging?
  - What resources did you consult?
    - Instructor? R or Quarto documentation, Websites (provide links)?
  - What more would you like to know about acquiring data?
    - Find potential resources you might consult to continue your learning. Provide links and a brief description of the resource.

## Submission for feedback

- Provide a link to your GitHub repository

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

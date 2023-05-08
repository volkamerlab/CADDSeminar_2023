# CADDSeminar_2023

__Teachers__
* Michael Backenköhler
* Paula Kramer
* Floriane Odje
* Andrea Volkamer


Link to [CS seminar](https://seminars.cs.uni-saarland.de/sose23seminars) description.

## General guidelines for each assignment

  1. Initial session: Research your topic and write the theory part of your notebook. You will be provided with some references but you are also expected to do some complementary reading if needed. On May 9th you will have to present it to the class (briefly).
  2. Work sessions (3 lessons): write your talktorial notebook. The final result should be comparable with [the notebooks from TeachOpenCADD](https://github.com/volkamerlab/teachopencadd). Please push your progress to this repo at **Monday 1 pm** the latest, so we have time to check your talktorials until **Tuesday** mornings.
  3. Presentation sessions (2 lessons): Present your notebook to the class.

## Course dates

The seminar will be on **Tuesdays**, starting at **10:15 am**.

Date   | Course content                                                               |
|-----:|:-----------------------------------------|
25.04. | Introduction and topic assignment
09.05  | Short presentations + Q&A
23.05. | Working on talktorials (I) + Q&A
06.06  | Working on talktorials (II) + Q&A
20.06  | Working on talktorials (III) + Q&A
27.06  | Student presentations (I)
04.07  | Student presentations (II)
11.07  | Student presentations (III)

## Topic assignments

Topic   | Name                                                               |
|-----:|:-----------------------------------------|
Diffusion-based docking model | Hamza Ibrahim
Scaffold-based data split     | Vahid Atabaigielmi
Protein Folding	              |	Mhd Jawad Al Rahwanji
Drug combination prediction with SVM	| Vanessa Siegel


## How to setup your notebook

1. Install [Miniconda for Python 3.7](https://docs.conda.io/en/latest/miniconda.html) in your OS.
2. Create a `conda` environment needed for your project, using `conda create -n <my_env>`.
3. Activate the environment with `conda activate <my_env>`.
4. Install jupyter notebook using `conda install jupyter notebook`. You will be able to install more when needed, but this is the basic one to start working on your notebook.
5. Run `jupyter notebook` and open the template notebook through the web-app.
6. You can find a conda cheat sheet [here](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).

## How to start working

1. Clone the _volkamerlab/CADDSeminar_2021_ repository, using `git clone https://github.com/volkamerlab/CADDSeminar_2021`.
2. Create a new branch called `T[mynb]-[your_initials]` (e.g. T01-AV_DS) using `git checkout -b T[mynb]-[your_initials]`.
3. Copy and paste the folder `0[nr]_topicname/` in `notebooks/` and rename it with your own topic number and topic name. This can be done using `cp -r notebooks/0[nr]_topicname notebooks/[mynb]_[mytopicname]` .
4. Rename the `talktorial_template.ipynb` notebook in your topic folder as `T[mynb]_[mytopicname].ipynb`. This can be done using `mv talktorial_template.ipynb T[mynb]_[mytopicname].ipynb`.
5. Activate the `conda` environment that you created in the previous section, using with `conda activate <my_env>`.
6. Run `jupyter notebook` and open your notebook `T[mynb]_[mytopicname].ipynb`.
7. Fill the template with the theory and start working.

## Version control
1. Save, stage and upload your changes using `git add <my_file>`, `git commit -m 'message associated to commit.' ` and `git push origin T[mynb]-[your_initals]`. __Be aware of the new files you add!__
2. You will now be able to create your pull request on GitHub on the `volkamerlab/CADDSeminar_2023` repo. Rename the title of your PR as `T[mynb]-[your_initials]`.

## Useful links & Cheatsheets
* [Conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
* Pythonic code: [PEP8 style](https://www.python.org/dev/peps/pep-0008/)
* [Numpy docstring](https://numpydoc.readthedocs.io/en/latest/format.html)
* Markdown [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)
* Git [cheatsheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
* [Gitmoji](https://gitmoji.carloscuesta.me/)

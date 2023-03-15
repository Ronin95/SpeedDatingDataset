# Visual Analytics Lab Project
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to GitHub.
Change/extend the corresponding sections by replacing the [TODO] markers.

For a detailed project spezification look up the [Visual Analytics Moodel page](https://moodle.jku.at/jku/course/view.php?id=20471).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information

### Group Members

| Student ID    | First Name  | Last Name      | E-Mail                  | Workload [%]  |
| --------------|-------------|----------------|-------------------------|---------------|
| k08925980     | Josef       | Schodl         | josef.schodl@gmail.com  |25         	   |
| k12114346     | Nikola      | Badjevic       | n.badjevic@gmail.com    |25             |
| k01608113     | Hao         | Zheng          | hao.zheng@hotmail.com   |25             |
| k12102933     | Hector      | Auvinen        | hectorauvinen@gmail.com |25             |

### Dataset

* What is the dataset about?
* Where did you get this dataset from (i.e., source of the dataset)?
* How big is the dataset?

**Description:**
- The dataset shows dating behavior using data from a Speed Dating experiment at a university where the authors generated random matching of subjects and created random variation in the number of potential partners. Furthermore, participants were surveyed about their demographic information, dating behavior, hobbys and what they look for in a partner. 
- Source: https://www.kaggle.com/datasets/whenamancodes/speed-dating?resource=download
- 5.19 MB - 195 columns - 8379 rows - .cvs file


## General Submission Information

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your executed submission notebooks as HTML and add them to your repository.  
  * Select 'File' -> 'Save and Export Notebook As...' -> 'HTML'
* Upload the exported HTML file on Moodle, if it is required for the submission.

## Usage

### Locally
Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/va-project-2022-vitamind.git
cd va-project-2022-vitamind
```

Load the conda environment from the `environment.yml` file, if you haven't already in previous assignments:

```sh
conda env create -f environment.yml
```

Activate the loaded conda environment:

```sh
conda activate python-tutorial
```

Install Jupyter Lab extension to use *ipywidgets* in JupyterLab:

```sh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should open a new tab with url http://localhost:8888/ and display the tutorial files.




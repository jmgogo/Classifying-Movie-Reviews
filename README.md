# Classifying Movie Reviews
<br />
<p align="center">
  <a href="https://github.com/jgome284/Classifying-Movie-Reviews">
    <img src="images\Python-to-Classify-Reviews.webp" alt="Logo">
  </a>

  <h3 align="center">Foreword</h3>

  <p align="center">
    Exploring the Stanford large movie review dataset with machine learning classifiers like k-nearest neighbors (KNN), logistic regression, and support vector machines (SVM).
    <br />
    <a href="https://github.com/jgome284/Classifying-Movie-Reviews/issues">Report Bug</a>
    ·
    <a href="https://github.com/jgome284/Classifying-Movie-Reviews/issues">Request Feature</a>
  </p>
</p>


<!-- TABLE OF CONTENTS -->
## Table of Contents
<div style='text-align:'>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#access-data">Access Data</a></li>
        <li><a href="#environment">Installation</a></li>
        <li><a href="#dependencies">Dependencies</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project
[Classifying Movie Reviews](https://github.com/jgome284/Classifying-Movie-Reviews)

In [this notebook](notebook.ipynb), machine learning classifiers like k-nearest neighbors (KNN), logistic regression, and support vector machines (SVM) are used to classify movie reviews.

<!-- GETTING STARTED -->
## Getting Started

To recreate this project locally, you can clone this repository via HTTPS as follows.

```sh
git clone https://github.com/jgome284/Classifying-Movie-Reviews.git 
```
### Access Data
The data utilized for this analysis is stored in a tar.gz file. This file is a combination of a .tar file and a .gz file. It is an archive file with several other files inside it, which is then compressed.

To access the IMDB moview review data set, you can unzip these files the same way you would unzip a regular zipped file in linux like so:

```sh
tar xvzf aclImdb_v1.tar.gz
```

### Environment
Virtual environments are a great way to keep your system-wide Python installation clean and organized. Each virtual environment is isolated from the others, so changes you make to the packages in one virtual environment will not affect the packages in another virtual environment. This can help to prevent conflicts between packages that are used by different projects.

**Create**

 You can create a virtual environment named my_env to manage this projects dependencies, for example. To do so, run the following command:
```sh
python -m venv my_env
```

**Activate**

To activate the virtual environment on Windows, run the following command:
```sh
source my_env/Scripts/activate
```

**Deactivate**

To deactivate the virtual environment, run the following command:
```sh
deactivate
```

### Dependencies
Python version 3.9.6 was used to run this analysis. To install additional dependencies, run the following command:
```sh
pip install -r requirements.txt
```
Best practice is to install these dependencies into an activated virtual environment. ```pip``` should be smart enough to handle dependencies between all packages required during installation.

### Download Spacy Model
```sh
python -m spacy download en_core_web_sm
```

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

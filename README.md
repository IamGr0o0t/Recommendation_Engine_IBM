# Recommendation Engine IBM




### Table of content
---------------
* [Motivation](https://github.com/IamGr0o0t/Recommendation_Engine_IBM#motivation)
* [Installation](https://github.com/IamGr0o0t/Recommendation_Engine_IBM#installation)
* [Software versions](https://github.com/IamGr0o0t/Recommendation_Engine_IBM#software-versions)
* [File descriptions](https://github.com/IamGr0o0t/Recommendation_Engine_IBM#file-Descriptions)
* [Results and Findings](https://github.com/IamGr0o0t/Recommendation_Engine_IBM#results-and-findings)
* [Licensing, Authors, Acknowledgements](https://github.com/IamGr0o0t/Recommendation_Engine_IBM#licensing-authors-acknowledgements)

### Motivation
---------------
Building recommendation engine for IBM users with articles on the IBM Watson Studio platform. Project contains knowledge based(rank based), user-user (collaborative filtering) and  content based recommendations with NLP, also matrix factorization to make accurate recommendations for  users on the IBM Watson Studio platform.

### Installation
---------------
All packages i have used were installed via most recent conda distribution.
```bash
conda 4.8.3
```
If you wish to install some other packages please feel free and do it with conda-forge.
```bash
conda install -c conda-forge (Insert Package Here)
```
### Software versions
---------------
* Anaconda version == 4.8.3
* Python version == 3.7.6
* pandas version == 1.0.1
* Numpy version == 1.18.1
* matplotlib version == 3.1.3
* seaborn version == 0.10.0
* scikit-learn version == 0.22.1

### File descriptions
---------------
There are 2 files related to data provided.
* data
|- user-item-interactions.csv (data about IBM users and their interactions with IBM Watson Studio articles.)
|- articles_community.csv (all articles available on IBM Watson Studio platform)

* project_tests.py (python file for assessing the functions within notebook)
* Recommendations_with_IBM.ipynb (jupyter notebook file containing all python script needed for recommendations)
* user_item_matrix.p (pickle file)

### Results and Findings
---------------
* By applying all kinds of recommendation techniques one can accurately reccomend articles available to new and existing users. Natural language processing techniques can be really handy to reccomend similar articles based on content of article.

### Licensing, Authors, Acknowledgements
---------------
This datasets are part of IBM Watson Studio.<br>
Thanks to [Udacity.com](https://classroom.udacity.com) for an amazing Data Science course.

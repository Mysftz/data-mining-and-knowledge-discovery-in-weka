<a name="readme-top"></a>
<div align="center">

[![alt text](https://github.com/Mysftz/Mysftz/blob/main/assets/READMEHeader.jpeg?raw=true)](https://github.com/Mysftz)
# Data Mining & Knowledge Discovery in WEKA
[![GitHub][GitHub-shield]](https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka)
[![Contributors][contributors-shield]](https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka/graphs/contributors)
[![Forks][forks-shield]](https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka/network/members)
[![Stargazers][stars-shield]](https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka/stargazers)
[![Issues][issues-shield]](https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka/issues)
[![License][license-shield]](https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka/blob/main/LICENSE.txt)
</div>

<p align="center">
  <a href="#about-the-project">About The Project</a> •
  <a href="#built-with">Built With</a> •
  <a href="https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka/archive/refs/heads/main.zip">Download</a> • 
  <a href="#usage">Usage</a> •
  <a href="#license">License</a> •
  <a href="#other-projects">Other Projects</a> •
  <a href="#contact">Contact</a>
</p>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#introduction">Infomation</a></li>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#other-infomation">Other Infomation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#other-projects">Other Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
### Introduction

The dataset given contains two classes of data, H1N1 (swine flu) and COVID 19 which contains various attributes: sex, symptom, etc. Utilising a decision tree classifier to split the class into a true or false statement to allowing for more accurate treatment of the attributes to be learnt. The first step is to pre-process the data, first removing all the p'' to have strings that python could process by selecting all the object type columns. Then transforming all the columns with strings into two columns for each to have 1 or 0 for the algorithm. The get dummies function from pandas was used and removed the columns where the values were "?".  For columns containing numbers, fill NaN to replace all null values with the average of the column.Then, to get the target the algorithm aims, transforming the strings "COVID" and "FLU" into 1 and 0. After processing the data, the data is split, the target and the features. These two groups of data will be used by the algorithm so that it can know what to target by taking some features as input. To learn the decision tree for the algorithm, the scipy package was used. A decision tree was utilised since the data contained numerous columns with true or false values. Having boolean data allowed to have good branching and accuracy in my decision tree. 

Analysing the results, in which a 10-fold cross-validation score is implemented on 70% training and 30% test data, outputted the decision tree. The tree has the primary internal nodes that split the H1N1 and COVID data into various attributes until it reaches the leaf nodes, the data filters out the number of samples of the attributes in each node that learns onto the next. With an overall accuracy score of 91% of the testing data, with an overall error of 1\% error, tabulated and the 10-fold cross validation score, plotting this data, which highlights the error of the training data onto the testing data. The decision trees nodes learn the most sampled attributes first and then splits into other attributes such as a symptom first and then learns the male and female attributes of that individual symptom regardless of the class. The tree splits true or false for the H1N1 and COVID 19 classes, however the most learnt attribute is age more so on the H1N1 class, this indicates that COVID 19 is broad in age brackets that H1N1. Regardless of class however, the ‘Age’ attribute is important as it’s fast identifier to those who are more susceptible to get either H1N1 or COVID 19, whereas the attributes: diabetes, serumlevelsofwhitebloodcells and lymphocytes are not as fast to identify, this is why the tree learns these attributes first as they aren’t unique attributes compared to the rest of the data.


### Built With

Python, Jupyter Notebooks, matplotlib, pandas, sklearn

### Other Infomation

LaTeX Report: https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka-report </br>
Python Files: https://github.com/Mysftz/data-mining-and-knowledge-discovery-in-weka

<p align="right">(<a href="#readme-top">back to top</a>)</p> 

<!-- USAGE -->
## Usage

This report was submitted for the degree of a Masters of Science in Computer Science (Artificial Intelligence) at the University of Kent in April 2022.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License
Distributed under the CC-BY-SA-4.0: Creative Commons Attribution Share Alike 4.0 International License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- OTHER PROJECTS --> 
## Other Projects
<div align="center">
<a href="https://github.com/stars/Mysftz/lists/data-science-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-DataScience.jpeg?raw=true" alt="Data Science Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/data-analysis-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-DataAnalysis.jpeg?raw=true" alt="Data Analysis Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/university-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-University.jpeg?raw=true" alt="University Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/python-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Python.jpeg?raw=true" alt="Python Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/latex-projects" style="margin:10px; padding-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Latex.jpeg?raw=true" alt="LaTeX Projects Button" width="265" height="75"></a>
<a href="https://github.com/stars/Mysftz/lists/other-projects" style="margin:10px; margin-bottom:50px"><img src="https://github.com/Mysftz/Mysftz/blob/main/assets/Button-Other.jpeg?raw=true" alt="Other Projects Button" width="265" height="75"></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
<div align="center">

GitHub: [@Mysftz](https://github.com/Mysftz) &nbsp;&middot;&nbsp; Portfolio: [Website](https://mysftz.github.io) &nbsp;&middot;&nbsp; LinkedIn: [@lrgtomaszewski](https://www.linkedin.com/in/lrgtomaszewski/) &nbsp;&middot;&nbsp; Instagram: [@Mysftz](https://www.instagram.com/mysftz/) &nbsp;&middot;&nbsp; Twitter: [@MysftzUK](https://twitter.com/MysftzUK)
</div>

[contributors-shield]: https://img.shields.io/github/contributors/mysftz/data-mining-and-knowledge-discovery-in-weka.svg?style=for-the-badge
[forks-shield]: https://img.shields.io/github/forks/mysftz/data-mining-and-knowledge-discovery-in-weka.svg?style=for-the-badge
[stars-shield]: https://img.shields.io/github/stars/mysftz/data-mining-and-knowledge-discovery-in-weka.svg?style=for-the-badge
[issues-shield]: https://img.shields.io/github/issues/mysftz/data-mining-and-knowledge-discovery-in-weka.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/mysftz/data-mining-and-knowledge-discovery-in-weka.svg?style=for-the-badge
[github-shield]: https://img.shields.io/badge/-GitHub-black.svg?style=for-the-badge&logo=GitHub&colorB=555
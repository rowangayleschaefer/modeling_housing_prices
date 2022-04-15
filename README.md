<div id="top"></div>


<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<h1 align="center">Ames Housing Data & Kaggle Challenge </h3>
  <img src="./images/houses9.png"> 

  <p align="center">
    Completed for General Assembly DSI Immersive
    <br />
    <a href="https://github.com/rowanschaefer/act_sat_analysis"><strong>Explore the data »</strong></a>
    <br />
    <br />
  </p>
</div>




<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents (Jump to section)</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      </ul>
        <li><a href="#built-with">Built With</a>
      </ul>
        <li><a href="#datasets">Datasets</a>
      </ul>
        <li><a href="#summary">Summary</a>
      </ul>
        <li><a href="#data">Data Dictionay</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<p>
</p>
<br>


<!-- ABOUT THE PROJECT -->
# About The Project

EXECUTIVE SUMMARY GOES HERE

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- BUILTWITH -->
## Built With

* [python](https://www.python.org)
* [jupyterlab](https://www.python.org)

<p align="right">(<a href="#top">back to top</a>)</p>

If you want to fork the repo and run this code, you will need python and Jupyter installed.
Check python version
  ```sh
  pip --version
  ```

Clone the repo
   ```sh
   git clone https://github.com/rowanschaefer/act_sat_analysis.git
   ```

<p align="right">(<a href="#top">back to top</a>)</p>
<p>

<!-- DATASETS -->
## Datasets

HOUSING DATA SET DESCRIPTION
AMES HOUSING DATA
For more info on these datasets, go to [example.com](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)

* [`act_2019_ca.csv`](./data/act_2019_ca.csv): Link and title goes here
* [`sat_2019_ca.csv`](./data/sat_2019_ca.csv): Link and title goes here



<p align="right">(<a href="#top">back to top</a>)</p>
<p>

<!-- SUMMARY -->
## Summary
### Process summary
* blah
* blah
* blah
* blah
<p>

### Data Cleaning
some more words here words words agsdg djddjdn vd ened  eehsjxjxcc nc cnxxx xxnx xsnssxxc fnffnd dend ddncd 
djcjc ddddnxnxnx xxnx sdu h ddjd  xb  ddhdhdhdd xxb x xx x x x wshwh whhhhhw ssd s sh z z z jubilate deo omnistera 
servite domino in lastitita
<p>

### Exploratory Analysis

some more words here words words agsdg djddjdn vd ened  eehsjxjxcc nc cnxxx xxnx xsnssxxc fnffnd dend ddncd 
djcjc ddddnxnxnx xxnx sdu h ddjd  xb  ddhdhdhdd xxb x xx x x x wshwh whhhhhw ssd s sh z z z jubilate deo omnistera 
servite domino in lastitita
<p>

### Modeling
blah blah balh balh blah  chddsdhb s sjhdsd ds lasso ridsge elasticnet
here's another image
<p>

### Conclusions:
* blah
* blah
* blah
<p align="right">(<a href="#top">back to top</a>)</p>
<p>

<img src="./images/div3.png">
<p><br />

<!-- DATA DICTIONARY -->

## Data Dictionary
*I don't think we need this for this project

|      Feature     |    Type     |   Dataset   |       Description              |
|---|---|---|---|
| **mini_cds**   |  *integer*  | 2010 census | The last 6 digits from a California School Code or CDS (City, District, School) code. Used to join dataframes. | 
| **school**  |  *object*    | 2010 census | Name of the school. Includes high schools in CA |
| **school_type**  |  *object*    | 2010 census | Type of school - i.e. charter schools, private, public. |
| **county**  |  *object*    | 2010 census | Name of the county the school is located in |
| **free_meal_eligibility**  |  *float*    | 2010 census | Percentage of students who qualified for free meals, average of years 2018 and 2019. |
| **freereduced_eligibility**  |  *float*    | 2010 census | Percentage of students who qualified for free or reduced meal plans, average of years 2018 and 2019.|
|    |    |   | *note, these two categories are not mutually exclusive.*|
| **sat_pct_math_benchmark**  |  *float*    | 2010 census | Percentage of students (both grade 11 and 12) who met the math benchmark on the SAT |
| **sat_pct_erw_benchmark**  |  *float*    | 2010 census | Percentage of students (both grade 11 and 12) who met the reading/writing benchmark on the SAT  |
| **act_pct_21**  |  *float*    | 2010 census | Percentage of students at the school who scored a 21 or higher on the ACT |
| **act_avgscore**  |  *float*    | 2010 census | Average ACT score of all students at the school |
| **act_avg_read**  |  *float*    | 2010 census | Average ACT reading subscore of all students at the school |
| **act_avg_math**  |  *float*    | 2010 census | Average ACT math subscore of all students at the school |
| **act_avg_sci**  |  *float*    | 2010 census | Average ACT science subscore of all students at the school |
| **act_avg_eng**  |  *float*    | 2010 census | Average ACT english subscore of all students at the school |
| **county_no_hs**  |  *float*    | 2010 census | Percent of adults living in the given county who do not have a high school diploma |
| **county_hs_only**  |  *float*    | 2010 census | Percent of adults living in the given county who have only a high school diploma |
| **county_somecollege**  |  *float*    | 2010 census | Percent of adults living in the given county who have an associate's degree or some college |
| **county_bachelorsplus**  |  *float*    | 2010 census | Percent of adults living in the given county who have a a bachelor's degree or higher|
| **zip**  |  *object*    | 2010 census | 5 or 10-digit zipcode of school |
| **latitude**  |  *float*    | 2010 census | latitude coordinates of school, used for mapping in tableau |
| **longitude**  |  *float*    | 2010 census | longitude coordinates of school, used for mapping in tableau |

<p align="right">(<a href="#top">back to top</a>)</p>
<p>


<!-- CONTACT -->
## Contact

Rowan - [@rowanschaefer](https://linkedin.com/in/rowanschaefer) - rgscha02@gmail.com

Project Link: [https://github.com/rowanschaefer/act_sat_analysis](https://github.com/rowanschaefer/act_sat_analysis)

<p align="right">(<a href="#top">back to top</a>)</p>
<p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* *thanks for the readme template [othneildrew](https://github.com/rowanschaefer/Best-README-Template)

<p align="right">(<a href="#top">back to top</a>)</p>
<p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png


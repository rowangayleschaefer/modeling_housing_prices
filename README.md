<div id="top"></div>

<h1 align="center">Ames Housing Data & Kaggle Challenge </h3>
<div align = 'center'> <img src="https://www.kindpng.com/picc/m/3-32823_house-drawing-png-transparent-png.png" height=150 width=230> </div>

  <p align="center">
    Completed for General Assembly DSI Immersive
    <br />
  </p>
</div>
<br />


<!-- ABOUT THE PROJECT -->
# About The Project

Predicting the sale value of a home can be difficult for homeowners who are looking to put their home on the market. The intention of this project is to create a "virtual home appraisal" model that can predict the sale price of a house in Ames Iowa, based on the features of the property. 

<br />


### Datasets
For this project I used only one dataset, the Ames Housing Dataset. 
The Ames Housing dataset was sourced and designed by Dr. Dean Decock for his undergraduate regression course. He wanted to give students a project that would mimic real life challenges in working with data, and expose students to issues they may encounter while trying to build models in the workforce. 

The original journal article about the creation of this dataset is here: [Ames, Iowa: Alternative to the Boston Housing Data as an
End of Semester Regression Project](http://jse.amstat.org/v19n3/decock.pdf).
The data contains over 70 columns of different features (nominal, discrete, and ordinal types) to describe properties in Ames, Iowa.
    
The data dictionary can be found [here](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt), or in the project files. 
<br />
<br />



### Software Requirements

NOTE: Github .ipynb rendering is a little broken for this project, likely due to the size of the notebooks. In order to view formatting and vizualizations  correctly, please fork/clone or download the repo and run on your local machine.

To run this code, you will need python (3.8.0 or higher) and Jupyter installed. <br />

Libraries used include:
* Pandas
* NumPy
* MatPlotLib
* Seaborn
* SciKitLearn

<br />


### Outcomes
Interestingly, my best scoring model for this project was a lasso regression with no feature selection whatsoever. This model ranked within the top 20% of the [Kaggle leaderboard](https://www.kaggle.com/competitions/321-countdown/leaderboard) with a score of  27292. 

This is not the best for interpretability, so given more time to complete the project, I would focus on limiting features.



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/rowangayleschaefer/modeling_housing_prices.svg?style=for-the-badge
[contributors-url]: https://github.com/rowangayleschaefer/modeling_housing_prices/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rowangayleschaefer/modeling_housing_prices.svg?style=for-the-badge
[forks-url]: https://github.com/rowangayleschaefer/modeling_housing_prices/network/members
[stars-shield]: https://img.shields.io/github/stars/rowangayleschaefer/modeling_housing_prices.svg?style=for-the-badge
[stars-url]: https://github.com/rowangayleschaefer/modeling_housing_prices/stargazers
[issues-shield]: https://img.shields.io/github/issues/rowangayleschaefer/modeling_housing_prices.svg?style=for-the-badge
[issues-url]: https://github.com/rowangayleschaefer/modeling_housing_prices/issues
[license-shield]: https://img.shields.io/github/license/rowangayleschaefer/modeling_housing_prices.svg?style=for-the-badge
[license-url]: https://github.com/rowangayleschaefer/modeling_housing_prices/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/rowanschaefer
[product-screenshot]: images/screenshot.png


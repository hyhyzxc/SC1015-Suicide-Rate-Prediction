# SC1015 SC5 Group 6 Mini Project - Suicide Prediction

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about">About The Project</a>
      <ul>
        <li><a href="#problem-definition">Problem Definition</a></li>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#dataset">Dataset</a></li>
      </ul>
    </li>
    <li><a href="#setup">Setup</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#models-used">Models Used</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
    <li><a href="#learning-points">Learning Points</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>

## About 

This is the repository for the SC1015 (Introduction to Data Science and Artificial Intelligence) Mini Project for group 6 under tutorial group SC5. 

<p align="right">(<a href="#top">back to top</a>)</p>

### Problem Definition
* Given a country's attributes (e.g GDP, Population, etc.) are we able to predict its suicide rate? 
* Which model will be the best to predict such a value?

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Scikit-learn](https://scikit-learn.org/stable/)

<p align="right">(<a href="#top">back to top</a>)</p>

### Dataset
Kaggle: [Suicide Rates Overview 1985 to 2016](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016) By Rusty

<p align="right">(<a href="#top">back to top</a>)</p>


## Setup
1. Run the command `pip install -r requirements.txt`
2. Explore the `.ipynb` file

<p align="right">(<a href="#top">back to top</a>)</p>

## Contributors
- [Bertranne Lee Zi - Wen](https://github.com/bertrainn) - Data Extraction, Code Refactoring, Formatting, Slides, Github and Video Creation
- [Goh Hong Yi](https://github.com/hyhyzxc) - Data Visualisation, Data Cleaning, Machine Learning and Slides
- Lee Wei Wen

<p align="right">(<a href="#top">back to top</a>)</p>

## Models Used
1. Linear Regression
2. Regression Tree
3. Random Forest (Regressor)
4. Gradient Boosting Regression Tree

<p align="right">(<a href="#top">back to top</a>)</p>

## Conclusion
* A country's suicide rate is not dependent on its age group, GDP/ Capita or generation
* Males are more prone to committing suicide than their female counterparts
* Random Forest has the highest accuracy and lowest RSME making it the best predictor for our problem statement

<p align="right">(<a href="#top">back to top</a>)</p>

## Learning Points
* Using data visualisation tools such as matplotlib and graphviz
* Converting categorical data to numerical data through label encoding
* Using decision tree for regression problems (i.e using a regressor tree)
* Improving the accuracy of a regression tree through bagging (Random Forest) and boosting (Gradient Boosting)
* Collaboration over Github

<p align="right">(<a href="#top">back to top</a>)</p>


## Acknowledgements
Dr Sourav Sen Gupta and TA Zhou Shao Wen: Thank you for your teaching and guidance over the course of this project. Your advice was invaluable in helping us make the best project possible. 

<p align="right">(<a href="#top">back to top</a>)</p>

## References
* https://www.sos.org.sg/learn-about-suicide/quick-facts
* https://www.geeksforgeeks.org/ml-label-encoding-of-datasets-in-python/
* https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/#:~:text=Random%20forest%20is%20a%20Supervised,average%20in%20case%20of%20regression.
* https://towardsdatascience.com/machine-learning-part-18-boosting-algorithms-gradient-boosting-in-python-ef5ae6965be4

<p align="right">(<a href="#top">back to top</a>)</p>

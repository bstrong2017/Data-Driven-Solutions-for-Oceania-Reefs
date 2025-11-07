<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>




<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Unlicense License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
 <p align="center">
  <img src="https://images.unsplash.com/photo-1546026423-cc4642628d2b?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1974"
       alt="Coral reef cover for Oceania Reefs project"
       width="100%" />
</p>

  <h3 align="center">Oceania Reefs: Data Driven solutions for Cost Effective Conservation</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://oceaniareefs.netlify.app/"><strong>Explore our website »</strong></a>
    <br />
    <br />
    &middot;
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

🐠🐠🐠🐠

Mass coral reef bleaching events have been prevalent for the last decade due to changes in the climate and environment. 
There are several factors that contribute to recent bleaching peaks in the Oceania region. 
Currently, there is no universal strategy for conservation, and many conservationists note that efforts are often expensive and time-consuming. 
This hinders the possibility of predicting potential bleaching events and saving impacted ecosystems. 
We used data from Kaggle’s Global bleaching environmental dataset to investigate increased coral bleaching. 
Using exploratory data analysis and predictive models on the Oceania coral reef data, we extract dominant environmental drivers. 
In a correlation analysis and heatmap, we identified the most influential factors that correlate with coral bleaching. 
These factors were included in our predictive models as the features that contribute to the predictive outcome. 
We found that climate factors such as temperature, thermal stress anomalies, and sea surface stress anomalies are the dominant causes of coral bleaching. 
Every year which mass bleaching events that have occurred in the past two decades are preceded by a high spike in climate temperature. 
Specifically, degree heating weeks, weeks where thermal temperature remains well above the recorded norm, are large contributors to bleaching. 
This information allowed us to build a baseline Linear Regression model, where we found that the relationship between coral bleaching and the selected environmental 
factors is not linear. In the comparison Random Forest model, we tuned the parameters and used Group k-fold cross-validation to observe the model’s performance, 
and found that this model captures 82% of the data’s variance. Using the trained model, we were able to create scenarios of bleaching events due to spikes in 
temperature and thermal stress anomalies. These scenarios mimicked real bleaching events that occurred in 2020, 2022, and 2024. Our findings concluded that data 
can be used to track bleaching events with moderate accuracy, and that the most important component of data-driven conservation is having recent and thorough recordings. 


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![python](https://img.shields.io/badge/Python-3.9-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
* [![jupyter](https://img.shields.io/badge/Jupyter-Lab-F37626.svg?style=flat&logo=Jupyter)](https://jupyterlab.readthedocs.io/en/stable)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Download the Python notebook file directly from GitHub or clone the project. This is a Python project, so all local environments will need Python dependencies and packages to start.
We would recommend that you visit the Kaggle website to observe the Global Bleaching Environment dataset and its documentation. 


### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free data set at [Kaggle](https://www.kaggle.com/datasets/pnminh95/global-bleaching-environmental)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Or download the ipynb file 
install



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This project can be used to improve coral bleaching prediction not only in the Oceania region but also in other coastal environments. The Random Forest model acts as a baseline for
improving the testing and training of environmental data. With more documentation and real-time data, this project can greatly impact early monitoring conservation. 


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Analyzed Kaggle Global Bleaching Environment Data set
- [x] Geospatial bleaching Analysis 
- [x] Correlation Analysis and Heatmaps 
- [x] Add "components" document to easily copy & paste sections of the readme
- [x] Predictive modeling
    - [x] Linear Regression model 
    - [x] Random Forest model
    - [x] Extreme Gradient Boosting model
    - [x] Support Vector Regression
- [x] RF Scenario Prediction temporal analysis
- [ ] Used trained Rf model on Real Time data 


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Top contributors:

* Brittany Strong
* Adora Buck
* Aiden Prashad 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the Unlicense License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

* Brittany Strong - [@brittany-strong-LinkedIn](https://www.linkedin.com/in/brittany-strong/) 
* Your Name - [@your-name](link)
* Your Name - [@your-name](link)

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [Kaggle](https://www.kaggle.com/datasets/pnminh95/global-bleaching-environmental)
* [National Oceanic and Atmospheric Administration](https://www.noaa.gov/)
* [GeeksforGeeks](https://www.geeksforgeeks.org/data-science/what-is-predictive-modeling/)
* [GitHub Pages](https://pages.github.com)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

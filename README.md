<div align="center">

  <img src="https://github.com/Mo-Shoba/Climate_Change_Sentiments/blob/main/Images/pexels-pixabay-163097.jpg" alt="logo" width="400" height="auto" />
  <h1>"Does This User Believe Climate Change is Man-Made?" 
  
  Tweets Classification Project</h1>
  
  <p>
    Classifying users as believers or non-believers in climate change being man-made
  </p>
  
  
<!-- Badges -->
<p>
  <a href="https://github.com/Louis3797/awesome-readme-template/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/Louis3797/awesome-readme-template" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/mo-shoba/King-MisuZulu-Coronation" alt="last update" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/network/members">
    <img src="https://img.shields.io/github/forks/mo-shoba/King-MisuZulu-Coronation" alt="forks" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/stargazers">
    <img src="https://img.shields.io/github/stars/mo-shoba/King-MisuZulu-Coronation" alt="stars" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/issues/">
    <img src="https://img.shields.io/github/issues/mo-shoba/King-MisuZulu-Coronation" alt="open issues" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/Louis3797/awesome-readme-template.svg" alt="license" />
  </a>
</p>
   
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Screenshots](#camera-screenshots)
  * [Getting Started](#toolbox-getting-started)
  * [Packages](#bangbang-prerequisites)
  * [Installation](#gear-installation)
  * [Roadmap](#compass-roadmap)
  * [Contributing](#wave-contributing)
  * [Contact](#handshake-contact)
  * [Acknowledgements](#gem-acknowledgements)
  

<!-- About the Project -->
## :star2: About the Project

 Many companies are built around lessening one’s environmental impact or carbon
footprint. They offer products and services that are environmentally friendly and
sustainable, in line with their values and ideals. They would like to determine how
people perceive climate change and whether or not they believe it is a real threat.
This would add to their market research efforts in gauging how their
product/service may be received.

Providing an accurate and robust solution to this task gives companies access to a
broad base of consumer sentiment, spanning multiple demographic and
geographic categories -

<!-- Screenshots -->
## :camera: Screenshots

<div align="center"> 
  <img src="https://github.com/Mo-Shoba/Climate_Change_Sentiments/blob/main/Images/Screenshot_2.png" width="600" height="600" alt="screenshot" />
</div>
The training data is quite imbalanced. The numerical labels on the x-axis were also changed for ease of comprehension. The numbers corresponded to the following: -1 == negative, 0 == neutral, 1==positive, 2==news.

To overcome this challenge, I attempted to use several techniques, including undersampling, oversampling and a combination of both techniques.


<div align="center"> 
  <img src="https://github.com/Mo-Shoba/Climate_Change_Sentiments/blob/main/Images/Screenshot_1.png" width="600" height="auto" alt="screenshot" /> 
</div>


 Here we have a screenshot of the top hashtags used per sentiment/category.
 
 
<div align="center"> 
  <img src="https://github.com/Mo-Shoba/Climate_Change_Sentiments/blob/main/Images/Screenshot_3.png" width="600" height="auto" alt="screenshot" /> 
</div>
 Here we have a screenshot of the final dataframe after the relevant natural language processing transformations have taken place (removal of stop words, lemmatization, etc.). In the final column, there is a prediction made on the previously unseen data.

<!-- Getting Started -->
## 	:toolbox: Getting Started
 
<!-- Packages -->
### :bangbang: Packages

These are the packages used:

```bash
re
string
numpy 
random
pandas==1.3.5 
matplotlib.pyplot 
advertools==0.13.1
nltk==3.6.5
wordcloud==1.8.1
string
spacy==3.2.4
```
Try the latest version on packages without versions

<!-- Installation -->
## :gear: Installation

Perhaps a package you may be unfamiliar with above is advertools. Advertools is an online marketing productivity and analysis tool. You can crawl websites, generate keywords for SEM campaigns, create text ads on a large scale, analyze multiple SERPs at once, gain insights from large social media posts, and get productive as an online marketer.

```bash
pip install advertools
# OR:
pip3 install advertools
```

<!-- Roadmap -->
## :compass: Roadmap

Climate change is an ongoing concern. As I write this readme, the 2022 United Nations Climate Change Conference is currently underway. It would be interesting to take a look at what people around the globe are saying on social networks about the discussions taking place there. 

* [ ] Todo 1 - Scrape the tweets around COP27 event (from 6/11/2022 to 18/11/2022)   
* [ ] Todo 2 - Begin analysis


<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/Louis3797/awesome-readme-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Louis3797/awesome-readme-template" />
</a>


Contributions and suggestions are always welcome!

You can contact me using my details below to get int touch.


<!-- Contact -->
## :handshake: Contact

Mlondi Shoba - Twitter: [@ushoba_](https://twitter.com/ushoba_)     Email: - msmshoba@gmail.com

Project Link: [https://github.com/Mo-Shoba/King-MisuZulu-Coronation](https://github.com/Mo-Shoba/King-MisuZulu-Coronation)


<!-- Acknowledgments -->
## :gem: Acknowledgements


 - [Advertools Package](https://advertools.readthedocs.io/en/master/)
 - [Readme Template](https://github.com/Louis3797/awesome-readme-template)

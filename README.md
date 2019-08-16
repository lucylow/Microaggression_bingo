# Microaggresion_Bingo &#x1F49C;
 
"**Death by a thousand papercuts**" // "**Winner Winner Privilege Dinner**"

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![GitHub Issues](https://img.shields.io/github/issues/lucylow/Microaggression_bingo.svg)](https://github.com/lucylow/Microaggression_bingo/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/lucylow/Microaggression_bingo.svg)](https://github.com/lucylow/Microaggression_bingo/pulls)
  [!. cense](https://img.shields.io/cran/l/devtools)]()
    
---

## Table_of_Contents &#x1F49C;

* [Game](#game-)
* [Definitions](#definitions-)
* [Screenshot of Game](#screenshot_of_game-)
* [Categories](#categories_config-in-bingooptions-)
* [Bingo Examples](#bingo_examples-) 
* [Technical How it works](#technical_how_it_works-)
* [Technical Facebook Developer Product Integration](#technical_facebook_developer_product_integration-)
* [Technical User Privacy Considerations](#technical_user_privacy_considerations-)
* [References](#references-) 


---
### Game &#x1F49. 
* A HTML5 bingo board mobile application exploring **social justice** and **privilege**. Participate in a fun, safe, and *inclusive* bingo game that *welcomes* players of diverse backgrounds!
* **Let's play the privilege game?** [Click here!]( https://lucylow.github.io/Microaggression_bingo/)

  <a href="https://lucylow.github.io/Microaggression_bingo/" >
    <img src="https://github.com/lucylow/Microaggression_bingo/blob/master/screenshots/microaggression_mini_logo.png" width="250" height="250"> </a>
    
    *Image. Microaggression mini logo "Winner Winner Privilege Dinner".*


  
---

## Definitions &#x1F49C;


**Patriarchy**
* "A cultural construct in which **old, rich, white, straight, cisgender, able-bodied, christian men** are valued more than minority groups."
* "Special rights, advantages, or immunity granted or available only to a particular person or group."


**Microaggression**
* "**Daily** verbal, behavioural, or environmental indignities, **whether intentional or unintentional**, that communicate **hostile**, **derogatory**, or **negative** prejudicial slights and insults toward any group."


**Explain Privilege to those who do not see it**
* Teacher tells students they are having a race and the winner recieves a prize. However, **some students get a head start** on this race:

  <a href="https://www.youtube-nocookie.com/embed/4K5fbQ1-zps
" target="_blank"><img src="http://img.youtube.com/vi/4K5fbQ1-zps/0.jpg" 
alt="Video to provoke discussion and understanding" width="240" height="180" border="10" /></a>


  *(Video. **”Every statement I’ve made has nothing to do with anything any of you have done.** We all know these people up here have a better opportunity to win this $100 bill.”)*


---

## Screenshot_of_Game &#x1F49C;


![Picture](https://github.com/lucylow/Microaggression_bingo/blob/master/screenshots/win%20state%202.png)


*Image. **User triggers the win state by matching five boxes in a row**. The popup **"Winner Winner Privilege Dinner"** appears and **win.mp3 audio** is played.*


---

## Categories_[Config in bingo.options] &#x1F49C;

* **Basic bingo board**
  * Pink background jpeg
  
* **Configurations**
  * Gender
  * Race
  * Age
  * Class
  * LGBT
  * Religion
  * Disabilities
  
* **Intersectionality**


---


## Bingo_Examples &#x1F49C;


* I am white.
* I am a man.
* My name is one of the following: [**James, John, Robert, Michael, William, David, Richard, Joseph, Thomas,** or **Chris**]
* I have never felt unsafe because of my gender, been catcalled, or raped.
* I have never been asked "So where are you *REALLY* from?", or "Why don't you have an accent?".
* I have never been a victim of violence because of my race.
* **I was not bullied as a child for any of my identities. :(**
* I have never been called fag/dyke/fairy or any other derogatory slur for homosexuals.
* I do not have any learning or physical disabilities.
* You have never heard this statement: "You have been *randomly selected* for secondary passport control".


---

## Technical_How_it_works &#x1F49C;


* **HTML5 + CSS3** 
  * Game transitions and animations
  * **Audio mp3s** for bingo sounds
  * Female voice intro **"Let's play the privilege game?"**


* **Javascript + jQuery**
  * Game reads customized .json **square microagression data** from data.js file
  * Content randomizes reload for new game each time 
  * Win state checks data attributes for winning bingo conditions
  * End game at "**Winner Winner Privilege Dinner**" popup


---

## Technical_Facebook_Developer_Product_Integration &#x1F49C;

* **HTML5 Games**
  * **Multi-platform devices** for accessible gaming experience
  * Integrates into new platforms like **FB instant Games**, or **Wechat**
  * Disadvantages: Graphical fidelity + Performance not as good as native + Battery life may suffer
    
    
* **Facebook Instant Games**
  * Web Instant Games bundle configuration in **fbapp-config.json** 
  * Easily publishes game to **app store** for users around the world
  
  
* **Facebook Login**
  * **Two-tap account creation** using Facebook-Profile
  * Asynchronously loads login in game, does not block loading other elements
  * Integrates with **Facebook Analytics** - requires *{your-app-id}* and *{api-version}*
  * Refer to documentation page from **Facebook for Developers** below:
 
  
  ![John](https://github.com/lucylow/Microaggression_bingo/blob/master/screenshots/FB%20Continue%20as%20John.png)
  
  
  *Image. Screenshot of the Facebook's "Continue as {Name} Button". [**The {Name} used is surprisingly John!**Facebook profile image of a white male and child. One can assume he has *"loving husband, father"* on his Twiter bio as well! ](#definitions-)
  
  
---
  
## Technical_User_Privacy_Considerations &#x1F49C;

* **HTML5 Local Storage Data**
  * Bingo cache stores data on user's local device
  * **Data.js information is removed when user clears cache**
  * Storage.setItem( 'game_state', JSON.stringify(gameState));


* **User.js File**
  * User.js file added for user privacy 
  * Template for **configuring privacy and security**
  * Reduce tracking from web analytics, tracking, finger-printing, or shoulder surfers
  * **Harden browser settings** against data disclosure or code execution vulnerabilities



---


## References &#x1F49C;


* How Priviledged Are you Buzzfeed Quiz: https://www.buzzfeed.com/regajha/how-privileged-are-you
* Top 10 Male Names: https://duckduckgo.com/?q=top+10+male+names&atb=v1-1&ia=web
* Developers Circles 2019: https://developercircles2019.devpost.com/?ref_content=featured&ref_feature=challenge&ref_medium=discover
* User.JS file : https://github.com/pyllyukko/user.js/tree/relaxed
* Facebook Instant Games: https://developers.facebook.com/docs/games/instant-games/getting-started/launch-checklist
* Facebook Login Integration: https://developers.facebook.com/docs/facebook-login/web



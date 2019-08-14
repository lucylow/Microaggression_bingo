# Microaggression Bingo &#x1F49C;

<div>
  
  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![GitHub Issues](https://img.shields.io/github/issues/lucylow/Microaggression_bingo.svg)](https://github.com/lucylow/Microaggression_bingo/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/lucylow/Microaggression_bingo.svg)](https://github.com/lucylow/Microaggression_bingo/pulls)
  [![License](https://img.shields.io/cran/l/devtools)]()

</div>

---
## Game &#x1F49C;
* A HTML5 bingo board mobile application exploring **social justice** and **privilege**.
* Participate in a fun, safe, and *inclusive bingo game that *welcomes players of diverse backgrounds.
* Slogan == **Death by a thousand papercuts**.
* Let's play the privilege game? https://lucylow.github.io/Microaggression_bingo/


  <img src="https://github.com/lucylow/Microaggression_bingo/blob/master/microaggression_mini_logo.png" width="250" height="250">




## Definitions &#x1F49C;

**PATRIARCHY**
* "A cultural construct in which **old, rich, white, straight, cisgender, able-bodied, christian men** are valued more than minority groups."
* "Special rights, advantages, or immunity granted or available only to a particular person or group."

**MICROAGGRESSION**
* "Daily verbal, behavioural, or environmental indignities, **whether intentional or unintentional**, that communicate **hostile**, **derogatory**, or **negative** prejudicial slights and insults toward any group."

---

## Screenshot of Game &#x1F49C;
![Picture](https://github.com/lucylow/Microaggression_bingo/blob/master/win%20state%202.png)

(Image of winning bingo board game state)

## Categories [Config in bingo.options] &#x1F49C;
* Basic bingo board
  * Pink background jpeg
* Configurations 
  * Gender
  * Race
  * Age
  * Class
  * LGBT
  * Religion
  * Disabilities
* Intersectionality

---

## Technical: How it works  &#x1F49C;

* **HTML5 + CSS3** 
  * Game transitions and animations
  * Audio mp3s for bingo sounds
  * Women's voice for : "Let's play the privilege game?"
  
* **Javascript + jQuery**
  * Game reads customized .json **square microagression data** from data.js file
  * Content randomizes reload for new game each time 
  * Win state **checks data attributes** for winning bingo conditions
  * End game at "**Winner Winner Privilege Dinner**" popup

---

## Technical: Facebook Developer Product Integration &#x1F49C;

* HTML5 Games
  * **Multi-platform devices** for accessible gaming experience
  * Integrates into new platforms like FB instant Games, or Wechat
  * Disadvantages: Graphical fidelity + Performance not as good as native + Battery life may suffer
    
* Facebook Instant Games
  * Bingo Board Web application hosting on Facebook Web Games
  * Instant Games bundle configuration in **fbapp-config.json** 
  * **Easily publishes game to app store** for users around the world
  
* Facebook Login
  * **Two-tap account creation** using Facebook-Profile
  * User does not need to create a password for account creation
  * Asynchronously loads login in game, does not block loading other elements
  * Integrates with **Facebook Analytics** - requires *{your-app-id} and *{api-version}.
  
  ![John](https://github.com/lucylow/Microaggression_bingo/blob/master/FB%20Continue%20as%20John.png)
  
  (FB's developer login button example - Continue as *John.)
  
---
  
## Technical: User Privacy Considerations &#x1F49C;
* HTML5 Local Storage Data
  * Bingo cache stores data on user's local device
  * **Data.js information is removed when user clears cache**
  * Storage.setItem( 'game_state', JSON.stringify(gameState));

* User.js File
  * **User.js file** added for user privacy 
  * Template for **configuring privacy and security**
  * Reduce tracking from web analytics, tracking, finger-printing, or shoulder surfers
  * **Harden browser settings** against data disclosure or code execution vulnerabilities


---

## Bingo Examples &#x1F49C;

* I am white.
* I am a man.
* My name is one of the following: [**James, John, Robert, Michael, William, David, Richard, Joseph, Thomas,** or **Chris**]
* I have never felt unsafe because of my gender, been catcalled, or raped.
* I have never been asked "So where are you REALLY from?", or "Why don't you have an accent?".
* I have never been a victim of violence because of my race.
* **I was not bullied as a child for any of my identities. :(**
* I have never been called fag/dyke/fairy or any other derogatory slur for homosexuals.
* I do not have any learning or physical disabilities.
* You have never heard this statement: "You have been randomly selected for secondary passport control".

---

## References &#x1F49C;
* How Priviledged Are you Buzzfeed Quiz: https://www.buzzfeed.com/regajha/how-privileged-are-you
* Top 10 Male Names: https://duckduckgo.com/?q=top+10+male+names&atb=v1-1&ia=web
* Developers Circles 2019: https://developercircles2019.devpost.com/?ref_content=featured&ref_feature=challenge&ref_medium=discover
* User.JS file : https://github.com/pyllyukko/user.js/tree/relaxed
* Facebook Instant Games: https://developers.facebook.com/docs/games/instant-games/getting-started/launch-checklist
* Facebook Login Integration: https://developers.facebook.com/docs/facebook-login/web



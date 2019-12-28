# Microaggresion_Bingo &#x1F49C;
 
"**Winner Winner Privilege Dinner"/ "We All Belong"**

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![GitHub Issues](https://img.shields.io/github/issues/lucylow/Microaggression_bingo.svg)](https://github.com/lucylow/Microaggression_bingo/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/lucylow/Microaggression_bingo.svg)](https://github.com/lucylow/Microaggression_bingo/pulls)
  [![License](https://img.shields.io/cran/l/devtools.svg)]()
   

![Picture](https://github.com/lucylow/Microaggression_bingo/blob/master/screenshots/win%20state%202.png)

*Image. **User triggers the win state by matching five boxes in a row**. The popup **"Winner Winner Privilege Dinner"** appears and **win.mp3 audio** is played.*   

---

## Table_of_Contents &#x1F49C;

* [Game Intro](#game_intro-)
* [Social Justice Motivation](#social_justice_motivation-)
* [Bingo Categories](#bingo_categories_config-in-bingooptions-)
* [Bingo Examples](#bingo_examples-) 
* [Technical How it works](#technical_how_it_works-)
* [Technical Facebook Developer Product Integration](#technical_facebook_developer_product_integration-)
* [Challenges I Ran Into](#Challenges_I_Ran_Into-)
* [Technical User Privacy Considerations](#technical_user_privacy_considerations-)
* [Books to Read for White Males Named J0hn](#Books_to_Read_for_White_Males_Named_J0hn-)
* [What's next for Microaggression Bingo](#What's_next_for_Microaggression_Bingo-)
* [References](#references-) 


---
### Game_Intro &#x1F49C;
* **A HTML5 bingo board mobile application exploring social justice and privilege** for Facebook's 2019 Developer Circle Challenge. Participate in a fun, safe, and *inclusive* bingo game that *welcomes* players of diverse backgrounds! Watch the video submission here: https://www.youtube.com/watch?v=WhfnhcWPI3U&feature=youtu.be
*  HTML5 games are games that users can **play on the web, across devices**. JavaScript can be used to create **immersive gaming experiences that are accessible to anyone** and can be integrated to platforms like Facebook Instant Games or Wechat. **Let's play the privilege game?** [Click here!]( https://lucylow.github.io/Microaggression_bingo/)
    
  <a href="https://lucylow.github.io/Microaggression_bingo/" >
    <img src="https://github.com/lucylow/Microaggression_bingo/blob/master/screenshots/marketing%20pics/schrodingers%20box.jpg" > </a>    
   
   *The bingo game is monitored by a pink cat named **Chris Schrodinger** who controls who can play this "free" game. He says **"Only 2D/3D boxes can play the game!"**. A shape named **Lucifer Yellowprism** says **"But we don't fit in the box!"**.*


  
---

## Social_Justice_Motivation &#x1F49C;


**Patriarchy**

* "A cultural construct in which **old, rich, white, straight, cisgender, able-bodied, christian men** are valued more than minority groups."
* "Special rights, advantages, or immunity granted or available only to a particular person or group."


**Microaggression**

* "**Daily** verbal, behavioural, or environmental indignities, **whether intentional or unintentional**, that communicate **hostile**, **derogatory**, or **negative** prejudicial slights and insults toward any group."


**Explain Privilege To Those Who Do Not See It**

* Teacher tells students they are having a race and the winner recieves a prize. However, **some students get a head start** on this race:


  <a href="https://www.youtube-nocookie.com/embed/4K5fbQ1-zps
" target="_blank"><img src="http://img.youtube.com/vi/4K5fbQ1-zps/0.jpg" 
alt="Video to provoke discussion and understanding" width="240" height="180" border="10" /></a>



  *(Video. **”Every statement I’ve made has nothing to do with anything any of you have done.** We all know these people up here have a better opportunity to win this $100 bill.”)*


---

## Bingo_Categories_[Config in bingo.options] &#x1F49C;

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
  * Dangers of One Sided Story
  * Echo Chambers

---


## Bingo_Examples &#x1F49C;


* I am white.
* I am a man.
* My name is one of the following: **[James, Chris, Robert, Michael, William, David, Richard, Joseph, Thomas, or J0hn]**
* I have never felt unsafe because of my gender, been catcalled, or raped.
* I have never been asked "So where are you *REALLY* from?", or "Why don't you have an accent?".
* **I was not bullied as a child for any of my identities :(**


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
  
  
  Image. Screenshot of the Facebook's "Continue as {Name} Button". **The {Name} and image of  Facebook profile is *suprisingly* WHILE MALE NAMED JOHN AND CHILD.** One can deduce he has *"loving husband, father"* on his Twitter bio. THIS IS BAD BECAUSE IT FURTHER REINFORCES THE PATRIARCHY. [Refer to social justice motivation definition above.](#social_justice_motivation-)
  
  
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

----

## Challenges_I_Ran_Into &#x1F49C;

* Game was super boring with a **"fixed"/"hard-coded" bingo board** 
   * Decided to **make game configurable** with json data so that user can choose tile names and it also **randomizes with each refresh**. 
* Uploading the **raw code to Facebook's HTML5 Instant Game platform** was quite a process. Had to read through documentation to **integrate facebook login, fbapp-config.json, analytics**, and the continue as {Name} button.
* **Accounting for user privacy**
  * In a bingo board game when the bingo cache stores data on user's local device
  * Decided that **data.js information be removed when user clears cache**


----

## Books_to_Read_for_White_Males_Named_J0hn &#x1F49C;

**According to statitsics in the US, WHITE MALES constitute only 33% of the population but they occupy approximately 80% of tenured positions in higher education, 80% of the House of Representatives, 80-85% of the U. S. Senate, 92% of Forbes 400 executive CEO-level positions, 90% pf public school superintendents, 99.9% of athletic team owners, 97.7% of US presidents. Here are some books for white males to read to better understand their privelege:**

 * Algorithms of Oppression: How Search Engines Reinforce Racism
 * Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor
 * Programmed Inequality: How Britain Discarded Women Technologists and Lost Its Edge in Computing
 * Weapons of Math Destruction: How Big Data Increases Inequality and Threatens Democracy <3
 * Dark Matters
 * Race After Technology: Abolitionist Tools for the New Jim Code
 * The Age of Surveillance Capitalism: The Fight for a Human Future at the New Frontier of Power
 * Artificial Unintelligence: How Computers Misunderstand the World 
 * Through Google-Colored Glass 
 * Invisble Women: Data Bias in a World Designed for Men <3
 * You Look Like a Thing and I Love You
 * The Intersectional Internet: Race, Sex, Class, and Culture Online
 * Brotopia: Breaking Up the Boys' Club of Silicon Valley 
 * Behind the Screen: Content Moderation in the Shadows of Social Media
 * Technically Wrong: Sexist Apps, Biased Algorithms, and Other Threats of Toxic Tech

---

## What's_next_for_Microaggression_Bingo &#x1F49C;
* More FB product integration since it's already on the platform. Ship it via Instant Games


---


## References &#x1F49C;

* "How Privileged Are you?". Buzzfeed Quiz. https://www.buzzfeed.com/regajha/how-privileged-are-you
* Top 10 Male Names. https://duckduckgo.com/?q=top+10+male+names&atb=v1-1&ia=web and https://duckduckgo.com/?q=how+to+overthrow+the+patriarchy&t=h_&ia=about
* Harvard Implicit Bias Test. https://implicit.harvard.edu/implicit/selectatest.html
* Developers Circles 2019 Competition. Devpost. https://developercircles2019.devpost.com/?ref_content=featured&ref_feature=challenge&ref_medium=discover
* User.JS File for User Privacy Github. https://github.com/pyllyukko/user.js/tree/relaxed
* Facebook Instant Games Developer documentation. https://developers.facebook.com/docs/games/instant-games/getting-started/launch-checklist
* Facebook Login Integration. Developer documentation. https://developers.facebook.com/docs/facebook-login/we
* Responding to Microaggressions. https://advancingjustice-la.org/sites/default/files/ELAMICRO%20A_Guide_to_Responding_to_Microaggressions.pdf



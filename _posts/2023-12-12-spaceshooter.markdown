---
layout: posts
title:  "Space Shooter"
date:   2023-11-11 18:59:00 +0000
categories: work
highlight_home: true
tags: C++ SFML
header:
 overlay_image: "/assets/images/spaceshooter/space_overlay.png"
 teaser: "/assets/images/spaceshooter/space_overlay.png"
 caption: "Gameplay Screenshot"
---

Dodge asteroids, defeat foes, and dance with missiles in this cosmic space escapade!

> To review the code files of this project, check out its GitHub repository at [Space Shooter on GitHub](https://github.com/nidhi-u/SpaceShooter).

### Introduction
Embark on a fun cosmic journey with my first SFML game project – a space shooter. Brace yourself for a classic gaming experience where you'll navigate through asteroid fields, engage in battles with enemy spaceships, and skillfully evade relentless missiles.

### Development Tools
I developed this project in Visual Studio using C++ and SFML (Simple and Fast Multimedia Library) - a graphics library that facilitates the creation of interactive applications. 

### Gameplay
In this 2D top-down game, the player controls a spaceship using wasd or arrow keys for movement. The player can shoot bullets by clicking the left mouse button. 
<br>
<br>
Asteroids rain from the top of the screen moving towards the bottom with varying speeds and having different sizes and consecutive damage dealt to player on collision. The player must dodge or destroy these asteroids. 
<br>
<br>
Enemy spaceships enter from the top of the screen and spawn missiles aimed at the player every few seconds until they are destroyed by the player. The missiles track the player and need to be shot down to avoid damamge. 
<br>
<br>
There is a health bar and a point counter at the top of the screen. 
<br>
<br>
Health packs move in the same way as the asteroids but are much rarer and restore some of the player's health when caught. Shooting a health pack howeber destroys it with no health restoration, discouraging the player from continuously shooting without aiming.
<br>
<br>
The diagram below summarizes the gameplay and shows the entities involved in the game - 
![Game Entities and their Functions](/assets/images/spaceshooter/elements.png){:width="500" height="500"}

### Game Demo
<video width="640" height="480" controls loop>
  <source src="/assets/images/spaceshooter/space_demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### Conclusion
Looking ahead, there's a lot I'm eager to do with this game. In the short term, I plan on adding animations, like flames from the spaceship engine and explosions for when entities collide. I also plan to add game music and sound effects to make the game more immersive and enjoyable. There's still plenty to learn and improve, but I'm excited for the next steps. In addition, I believe this project sets the stage for future adventures! The road ahead promises more creativity, more challenges, and undoubtedly, more fun.

<br>
<br>
<br>
<br>
<br>
<br>
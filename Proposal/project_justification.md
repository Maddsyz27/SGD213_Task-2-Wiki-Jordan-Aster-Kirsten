# Justification
[//]: # (This section is an example of justifying your design and development decisions.)

## Overview

### Brief
[//]: # (What was the client's brief?)
The client is seeking a proof of concept for a game that is simple, yet a leader in its class
**LIST ORIGINAL STATEMENT OF REQUIREMENTS**

### Communication
Art Style & Gameplay
* Could you provide some visual references or screenshots that represent the style and tone you are aiming for?
> Do not worry about intended visuals, as no assets are expected on your end: I will be able to adjust various values and settings on my end instead.
  
* Will the gameplay be 2D or 3D?
> I would love the more complex design space of the 3D shooter, so 3D would be the preference. 

Player Character Mechanics
* Should the player be able to carry multiple grenades?
> The player should be able to carry multiple grenades, since they would simply act as an ammo counter. If you meant different types, a weapon switching system you would need to implement would allow me to duplicate existing presets to create them during further development, so it wouldn't be a necessary addition on your end.

* Should the player be able to shoot both weapons?
> Both weapons should be functional, though they won't be able to be fired simultaneously.

* Should the player be able to throw grenades?
> Yes, the intent for the grenade to be throwable.

* Will players need to pick up weapons and grenades within the game world?
> That sounds like a great interaction. Perhaps a generic way to interact with items in the world and an equip function for the player? It would allow the project to be far more customizable down the road.

* Will guns have limited ammunition, or will they have infinite ammo?
> Ammo should be finite, though a simple toggle in the editor to make it infinite would be a good addition for prototyping/testing.

* Will the player and enemies have health systems to take and deal damage?
> Yes, both the player and the enemies need to have a health system that interacts with damage.

Enemy AI & Movement
* Will movement for both the player and enemies be limited to basic directions (forward, backward, left, right), or would you like additional actions such as running, crouching, or jumping?
> The movement should be fairly basic for this stage, with the addition of jumping for the player. As noted in the basic description, I just need the enemies to be able to patrol around and detect the player.

User Interface
* Would you like an in-game HUD displaying player stats such as health, ammo, current weapon, and grenade count?
> A minimal HUD for the various characteristics you've listed would be great to see, though as always, no assets are required: any UI elements are something I can adjust later and only need a system that reads current values from the player/enemies and feeds it to the HUD.

* Should we also include a start menu, pause functionality, and a quit option?
> A save point system sounds good, though non-critical. Perhaps we can keep it in mind as a final stretch goal.

* Is there a particular code structure or architecture you would like us to follow to help support your students or for further future development?
> When it comes to architecture and systems, the choices are up to you, since you'll have a better idea of the ideal approach once the requests and requirements are considered.

* Will the player have the ability to heal after taking damage? If so, should this be facilitated through health pickups found in the game environment, or through health pickups added to the player's inventory and used when needed by the player?​
> The player healing through pickups is a great addition, though it should be immediate after the player walks over it, as no inventory system is required for the prototype.

* Is the game intended to be single-player only, or are there plans to incorporate multiplayer functionality?​
> Single player only.

* Which platform(s) is the game expected to run on (e.g., PC, console, mobile)?​
> The only current platform is PC.

* Do you have a specific location or environment in mind for the game's setting, or would basic geometric designs suffice for the intended experience?​
> Basic geometric designs would be sufficient for the prototype.

* Could you please confirm the due date for the project being 1 June, 2025?​
> Yes, the due date for the project is 1st of June, 2025.

* What is the approximate age bracket of the students who will have access to the game?
> The current age bracket is likely 18-25, though you are free to experiment with the placeholder content for the project as it will be able to be adjusted later.

---

## Project Understanding

### Requirements
[//]: # (What are the requirements of the finished project?)
* Needs the product in 5 weeks.
* Gameplay should be fast-paced
* Rounds should be short
* Should be quick to restart
* Feedback is a major point
* People should be drawn to it by it's appearance
    * Needs a catchy name

### Expectations
[//]: # (What are the client's expectations?)
* Project delivered on time
* Weekly updates on progress
* Communication with the client when design issues encountered
* Quality transparent project management (add the client)
* Does **not** require audio
* Does **not** require high quality art
    * Can use basic geometry
    * Should still look nice using colour palettes

### Assumptions
[//]: # (What are you assuming based on client responses)
* 
* No other features of system requirements are required for the final build for the client beyond this brief.

---
## Risks

### Risks
[//]: # (What are the risks of this project)
* Our project developers have less experience and knowledge of the C# code that the project centres around, as well as limited use of unity as a game engine. This may require certain parts to take longer to complete, based on difficulty level. 
* Since this project has a concrete timeline as specified by the client, there are strict time constraints the project must follow, making it more likely to see the appearance of bugs and flaws in the coding. 
* Moreover, with the same idea of having such harsh time deadlines, developers need to consider cutting edges for the sake of overall functionality with some areas not being as fleshed out as desired. 

### Risk Management
[//]: # (How are you managing the mentioned risks)
* Consistent team communication, in the form of organised meetings, will be utilised to eliminate any coding conflicts and solve any current problems in discussion. 
* Our expectations for the project and its timeline will be kept at a feasible level, aiming to keep ideas both reasonable whilst aligning with client criteria. 
* Project testing will take place consistently throughout the development phase, to avoid only fixing flawed code and errors near the project’s finish.  

---

## Constraints

### Constraints
[//]: # (What are the constraints of this project)
* With a limited space of time in which the game will be constructed, decisions and general execution will need to be fast-paced and concise. 
* Having a development team that consists of only a few developers means that ideas and decisions may be more close-minded, given the lack of opinion variety. 
* Given the development team’s current experience with using C#, there may be issues with skill level that can hinder or prolong a task’s completion. 

---

## Justification
We really like the mention of "silly games catch people's eyes". So we took your suggestion of dragons and built on it with alliteration as a starting point. We went through many ideas, but finally came up with a title called "Donuts, Daggers & Dragons.

The name along was enough to get conversation happening, and we soon found ourselves thinking of countless, comical and enjoyable scenarios stemming from the title.

etc. Explain your design decisions in regards to the client's requirements.

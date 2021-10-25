# MDDV - Unreal Engine (Final project)

## "Ghostly Manor"

> *Welcome to **Ghostly Manor**, your new home! You just bought an awesome house for an awesome price, don't let its name (or the fact that you were the only one at the open house) get you mad.
> We're going to give you a classy and completely normal gift to debut your new home: a ball gun and a robotic suit.*
> 
> *Maybe I forgot to mention something: we couldn't get rid of the last tenants, they are so in love with this house that they even hid in the paintings.*
> 
> *PS: They're afraid of yellow spheres, so don't let them touch you if you don't have any near!!!!*
> 
> 
> *Cheers and please keep alive! ~~I don't want to scam someone again~~ get throgh this again. *
> 
> ***Miriam López Sierra - Real State Agent***
> 
> (NO REFUNDS ACCEPTED)


![alt Ghostly Manor](https://github.com/mirlop01/Unreal-project/blob/master/Content/House/Images/Ghostly%20manor.png)


## Game design

This game is simple: you have to achieve the highest score without dying.

### Player
You will control an android whose task will be end with the ghost tenants. For this purpose you'll have a gun that shoots yellow balls.

You'll have to hit them a couple of times before they dissapear (the remaining health will be displayed on top of the enemy as a red progress bar)

### Enemies
The enemies are ghosts, 

![alt Ghost minding its business](https://github.com/mirlop01/Unreal-project/blob/master/Content/House/Images/Ghost.png)

they will be running on their own until they see you, and at this point two things can happen:

- If you have the weapon -> They will try to steal it from you.
- If you don't have it -> You better run, they will try to kill you.

If any of the ghosts has stolen your weapon it will glow with a yellow light and will run away from you, but remember, the other ghosts will still be trying to kill you!

![alt Thief ghost](https://github.com/mirlop01/Unreal-project/blob/master/Content/House/Images/Evil_ghost.uasset)

**Pickups**
You have some pickups spawners in order to recover health

![alt Health pickup](https://github.com/mirlop01/Unreal-project/blob/master/Content/House/Images/Health_pickup.png)

or ammo.

![alt Ammo pickup](https://github.com/mirlop01/Unreal-project/blob/master/Content/House/Images/Ammo_pickup.png)

It will be automatically and randomly generated after being taken.

### Levels
You will **level up** everytime you kill all the enemies on the manor. 
As you level up, more ghosts will spawn.

![alt Thief ghost](https://github.com/mirlop01/Unreal-project/blob/master/Content/House/Images/Level%20up.png)

## Game development
This game has been design and created in Unreal engine.
The Scenery was created using the starter content meshes that are provided by the First Person Shooter Example.
![alt Ghostly manor ](https://github.com/mirlop01/Unreal-project/blob/master/Content/House/Images/Ghostly_manor_Out.png)

The mechanics were developed using blueprints.

### Enemies
The enemies behaviour were developed using basic AI. For this we used a [behaviour tree](https://github.com/mirlop01/Unreal-project/tree/master/Content/Blueprints/Enemy).

## References
- Documentation given in the course
- https://docs.unrealengine.com/4.26/en-US/RenderingAndGraphics/Materials/HowTo/EmissiveGlow/
- https://docs.unrealengine.com/4.26/en-US/Resources/SampleGames/ARPG/AddingAPickUp/
- https://www.youtube.com/watch?v=zNJEvAGiw7w&ab_channel=RyanLaley
- https://mixkit.co/free-sound-effects/game/?page=2

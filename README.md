# VREmotionalExperience

This project was created with in collaboration with two other game developers and two fashion students for Therapieland, a e-health company.
The main purpose of the game was to frustrate the player while still being engaging. The use-case for this project was at a therapist office for clients with anger management issues. By taking them out of the real world and frustrating them in a virtual environment, the therapist could work together with their client without being the focus of their anger. It also creates a frustrating situation, making it easier to recognize the emotions while they are happening.
My main contributions were the SteamVR optimizations, the gameplay and visuals for the "puzzle" with the shapes, gravity field and visuals, the walking (annoying) robot, and connecting a bluetooth heartrate monitor to the game and displaying this through heart visuals.
We've had great results during our playtests. People were getting frustrated while still having fun. They really wanted to complete the challenge! We've had people shout at and try to punch the robot, controllers hitting the wall of our small space due to angrily throwing the shapes and running out of the playing field (with everything attached) because they got so immersed.

The room with shapes:

![](https://i.imgur.com/WgObHYg.png)

You have to throw the (abstract) shapes near the correct holographic shape. If it's the correct shape, they'll get sucked in by a simulated gravity field.. since we're in space.

![](https://i.imgur.com/myr9YB3.png)

Robot will take the shapes that have been successfully placed after x amount of seconds and reset them to the other side of the room.

![](https://i.imgur.com/QjD1Tyn.png)

If the player teleports close to the shapes to pick them up, there's a set chance for it to fall through the ground and drop back down on a different spot

![](https://i.imgur.com/FrIRaCW.png)

The game will frequently ask the player through audio how they feel and that they should pick their emotion. This audio keeps looping itself frequently until an emotion has been picked, only to start its sequence again soon.

![](https://i.imgur.com/b1NgPBp.png)

I used the UWP bluetooth LE example from microsoft to connect a heartrate monitor to Unity. I displayed the heartrate through heart visuals on the wall that beat at the same speed as the current heartrate.

![](https://i.imgur.com/mk8gpOK.png)


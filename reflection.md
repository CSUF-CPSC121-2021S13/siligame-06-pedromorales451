# Milestone 2

## Description
Describe what you did for this milestone in your own words.

In this milestone, I had to modify my code to use pointers instead of constant references, and had to create and store unique pointers to the game objects. First, for the GameElement class I had to change the parameters of the IntersectsWith member function from constant references to pointers. I then had to update all the functions that utilized the IntersectsWith function to accept pointers. I also had to implement many member functions, such as the LaunchProjectile function to return a unique pointer to an opponent’s projectile. For the Game class, I had to create vector data members that stored unique pointers to game objects. I then had to modify any functions or code that used the old vectors from the previous milestone. I also had to implement functions that created and launched projectiles on the game screen, checked for intersections, and remove inactive objects. Lastly, I had to implement functions that checked for mouse events to determine if player projectiles should be created and to display the player’s score. 

## Challenges encountered
Describe the challenges you encountered while working on this milestone of the project.

One of the biggest challenges that I encountered was working with pointers and unique pointers. I found working with pointers challenging because when I had to modify other member functions, I had to make sure to use proper syntax and I had to know when to use std::move. Although there was plenty of functions to modify because of the use of unique pointers and vectors that store unique pointers, I made use of compilation errors to direct me to the functions that needed to be fixed. 

## Things I've learned
What is the most important thing you've learned from this milestone in the project?

The most important thing that I have learned from this milestone is how to use unique pointers and pointers to modify my code and make it more efficient. It was really interesting to see how differently code has to be written in order to use unique pointers and pointers. By using unique pointers, I got a chance to practice how to use std::move and unique pointer syntax.  

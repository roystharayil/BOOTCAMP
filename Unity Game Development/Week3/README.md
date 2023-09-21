
# Week 3

## Topics

1. Animations
2. Particle System
3. Audio
4. Materials



## Exercises

### 1. Animations:
**Exercise 1.1: Basic Animation**  
Objective: Create a simple animation for a cube.
- Create a new 3D Cube in your scene.
- Open the Animation window (Window > Animation > Animation).
- Click on the Cube and then click on "Create" in the Animation window.
- Animate the cube to move up and down over a span of 3 seconds.
- Play the animation to see the cube moving.

**Exercise 1.2: Animation Transition**
Objective: Use Animator to transition between two animations.
- Create two animations for the cube: One moving it left and right, and another rotating it.
- Use the Animator window (Window > Animation > Animator) to create transitions between these animations.
- Add a trigger to control the transition.
- Test the animations in play mode using a simple script to trigger the transition.

### 2. Particle System:
**Exercise 2.1: Basic Particle Creation**  
Objective: Create a simple particle system.
- Create a new Particle System in your scene.
- Experiment with the emission, shape, and color over lifetime modules to create a basic fountain effect.

**Exercise 2.2: Fire Effect**  
Objective: Create a realistic fire effect.
- Using the Particle System, try to simulate a fire. Adjust properties such as start color, size over lifetime, emission rate, and add some noise.
- Bonus: Add another Particle System as a child to simulate smoke.

### 3. Audio:
**Exercise 3.1: Background Music**  
Objective: Play a background music track.
- Import an audio clip into your project.
- Create an empty GameObject and attach an AudioSource component.
- Assign your audio clip to the AudioSource and enable loop.
- Play the scene and listen to the background music.

**Exercise 3.2: Triggered Sound Effect**  
Objective: Play a sound effect when entering a trigger zone.
- Create a 3D Cube in your scene representing a trigger zone.
- Attach a Box Collider component to it and set it to "isTrigger".
- Create a script that plays a sound effect when the player enters the trigger zone.
- Test the effect by moving an FPS character into the cube.

### 4. Materials:
**Exercise 4.1: Basic Material Creation**  
Objective: Create a new material and assign it to a GameObject.
- Create a new Material in your project.
- Change its color and adjust its smoothness.
- Create a 3D Sphere in your scene and assign your new material to it.

**Exercise 4.2: Texture Mapping**  
Objective: Apply a texture to a material.
- Import a texture into your project.
- Create a new Material and assign the texture to its Albedo slot.
- Create a 3D Cube and apply this material.
- Adjust the texture tiling and offset to achieve a desired look.


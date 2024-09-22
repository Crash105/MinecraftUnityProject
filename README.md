# Project 4: Interactive Scene Combination

## Links
- [Play on itch.io](https://machiner8.itch.io/brianmaina-project4)
- [Exported Files](https://drive.google.com/drive/folders/1W33Cx7kt8QZG0AsheKnh08RZD3H-iw u?usp=sharing)

## Scene Name
Project4_Scene

## Description
Project 4 combines elements from Projects 1, 2, and 3. It features two main buttons that direct users to different interactive scenes:

1. Project 3: Minecraft Creeper Manipulation
2. Projects 1 & 2: Shape Creation and Manipulation

### Project 3: Minecraft Creeper Manipulation
A prefabricated object resembling the Creeper enemy from Minecraft can be manipulated using six toggles:

- Rotate Toggle
- Scale Toggle
- Fast Scale Toggle
- Rotate and Scale Toggle
- Color Toggle
- Position Toggle

Only one toggle can be used at a time.

### Projects 1 & 2: Shape Creation and Manipulation
This scene includes:

- Color sliders (Red, Green, Blue) with associated text displays
- Toggles for object deletion, random rotation, and time display
- Clear button to delete all created objects
- Mouse position display
- Dropdown menu for shape selection

## Features

### Project 4 Main Features
1. **Project 1 and 2 Button**
   - Input: Left Click
   - Output: Loads Project 1 and 2 Scene

2. **Project 3 Button**
   - Input: Left Click
   - Output: Loads Project 3 Scene

### Project 3 Features
1. **Rotate Toggle**
   - Input: Left Click
   - Output: Rotates object from y=0 to y=270, then y=180, and back to y=0

2. **Scale Toggle**
   - Input: Left Click
   - Output: Gradually scales object to double its size

3. **Color Toggle**
   - Input: Left Click
   - Output: Gradually changes object color to dark blue

4. **Fast Scale Toggle**
   - Input: Left Click
   - Output: Scales object 3 times faster than Scale Toggle

5. **Scale and Rotate Toggle**
   - Input: Left Click
   - Output: Simultaneously scales and rotates object

6. **Position Toggle**
   - Input: Left Click
   - Output: Moves object in a square pattern

### Project 1 and 2 Features
1. **Display Mouse Position**
   - Input: Mouse movement
   - Output: Displays X and Y coordinates in upper left corner

2. **Paint Objects**
   - Input: Left click (hold), Right click
   - Output: Creates objects, right-click shrinks objects (Unity only)

3. **Change Primitive**
   - Input: Dropdown menu
   - Output: Changes shape of created objects

4. **Change Color**
   - Input: RGB sliders
   - Output: Adjusts object color, updates slider value text

5. **Clear Button**
   - Input: Left Click
   - Output: Destroys all user-created objects

6. **Delete Toggle**
   - Input: Left Click
   - Output: Disables automatic object destruction

7. **Rotate Toggle**
   - Input: Left Click
   - Output: Randomly rotates objects

8. **Turnoff Toggle**
   - Input: Left Click
   - Output: Hides time display

9. **Paint Grey Button**
   - Input: Left Click
   - Output: New objects are created in grey color

10. **Change Scale**
    - Input: Left Click
    - Output: Adjusts object size

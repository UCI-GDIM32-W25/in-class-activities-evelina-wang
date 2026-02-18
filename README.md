# GDIM32 In Class Activities

## W1
### Activity 1
Be sure the link can run before you submmit the homework!!! And don't be late

### Activity 2
    1.10
    2.2
    3. "Hello world" will be printed to the console every frame
    4.MonoBehaviour
    5.It will print "x=10" in the en
    6.Method argument and method parameter; used to pass input data
    7.Translate can only be called on an object. Transform is a class.
    8.Call Translate on the _playerTransform object instead of on the Transform class.

### Activity 3
[W1 inclass](https://docs.google.com/document/d/1k-sXYZ-8W-76zU_AhOm0KkVi5w6dVbUOzbarCw8tWbU/edit?tab=t.0)

## W2
### Activity 1

<img width="913" height="690" alt="a graphic breakdown of MG2" src="https://github.com/user-attachments/assets/410106ce-3d96-4b37-b613-ef95a3b9d083">

### Activity 3
Created the scene and added the script for the "ground and penguin colliding" effect. Enable the penguins to jump and allow them to make the next jump only when they touch the ground, and ensure there is a collision with the ground.
[W2 inclass](https://github.com/UCI-GDIM32-W25/mg2-evelina-wang/commit/e1aa8fc69fcdc2aa96b4f9b3924107bffc82ffc7)


## W3
### Acitivity 012
Ziying Huang
### Activity 3
<img width="913" height="690" alt="a graphic breakdown of MG2" src="https://github.com/user-attachments/assets/78b3a2bd-42db-4256-a1f8-c9d2f7ebbadd">


## W4
### activity 0
Ziying Huang
### activity 1
All target objects will exist in the scene simultaneously. Unity will instantiate and load them during the Start/Awake phase. Any logic in the script that references or searches for these objects will apply to each target object.
### acitivity 2
<img width="913" height="690" alt="a graphic breakdown of MG2" src="https://github.com/user-attachments/assets/73488648-47fd-43c0-adda-76457875b61d">


## W5
### activity 1
I think it is a good design. The separation between a common Item base class and an optional IBreakable interface shows good instincts about polymorphism and behavior-based design. I will keep it Item as an abstract base class Interfaces for optional behaviors (IBreakable).
### activity 2
Model is Player W5 Demo 2, view is inventory UI, controller is Enemy Stats
### activity 3
#### Scenarios 1
Inheritance with polymorphism, basic parent class that each type of beat can be scored, and the judging rules are the same. 
#### Scenarios 2
ScriptableObjects Used to store character configuration and skill data (damage, cooldown, animation names); adding a new character only requires creating new data, without modifying the code.
#### Scenarios 3
Create a parent class for FarmObject or Interactable, shared by all farm objects. Use interfaces to separate functionality, such as IPlantable, IHarvestable, IDestructible, so that rocks, crops, and seeds only implement the parts they need.
#### Scenarios 4
[W5 inclass](https://docs.google.com/document/d/10HReV1LS2bKpFumSkCfVwM0uvrhOadVoLUmLjYf7iTk/edit?tab=t.0#heading=h.y4j3q551ojs1)
Attendance: Nicole Yang, Evelina Wang, Ziying Huang

## W6
### activity 1
These class I know how tocheckt the FPS, some date and how to find the casuse of the lag, when our group make chasing interating.
[W6 final proposal](https://docs.google.com/document/d/10HReV1LS2bKpFumSkCfVwM0uvrhOadVoLUmLjYf7iTk/edit?tab=t.0)

### activity 2
Attendance: Nicole Yang, Evelina Wang,Ziying Huangs


## W7
### activity 1
use bool to check weather the player colse.In the Update() function, the program first checks whether the player is detected through Raycast (a combination of line-of-sight detection and LayerMask filtering). Then, based on the result, it switches the state and executes the corresponding behavior. In the patrolling state, the duck generates a random direction using Random.insideUnitCircle and detects whether there are obstacles in front of it through SphereCast to avoid colliding with walls. In the chasing state, it calculates the direction vector between itself and the player on the x/z plane, uses Vector3.RotateTowards to achieve smooth turning, moves towards the player, and sets a stop distance to prevent jittering.

### activity 2
to be continue... attendance: Evelina Wang Nicole Yang, Ziying Huang
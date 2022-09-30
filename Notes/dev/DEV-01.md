# DEV-01, Chapter 1: Armatures Intro

## Rigging Guinea Pig 

<img src="../images/DEV-01/DEV-01-A1.png" width="1100"/>

## Adding Bones
<img src="../images/DEV-01/DEV-01-A2.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-A3.png" width="1100"/>

    Managing view settings for bones

<img src="../images/DEV-01/DEV-01-A4.png" width="1100"/>

## Naming, Connecting and Parenting Bones
<img src="../images/DEV-01/DEV-01-B1.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-B2.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-B3.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-B4.png" width="1100"/>

    Renaming Bones

<img src="../images/DEV-01/DEV-01-B5.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-B6.png" width="1100"/>

    Make sure that the origin is at a reasonable spot so that if we plan to "symmitrize" it will make sense

<img src="../images/DEV-01/DEV-01-B7.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-B8.png" width="1100"/>

    The first click is the child, the second click is the parent. Then Ctrl P.
    2 divides the influence of 1 on the model

<img src="../images/DEV-01/DEV-01-B10.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-B11.png" width="1100"/>

    The large bone, "Root" on the floor is meant to match the orientation the the world.
    The Main, which is on the model is then parented to this Root bone. Then the bones on the model are parented to the Main.
    This will allow in pose mode to move the whole bone structure if you grab either the Root of the Main.

<img src="../images/DEV-01/DEV-01-B12.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-B13.png" width="1100"/>


## Setting Up IK Controls

    What is IK? Ik stands for inverse kinematics, and are useful when rigging parts like arms, legs and anywhere that bends.
    Its usually used to control joins that move in relation with each other.

    Add a new bone on top of the metagross leg, this will serve as our constraint. You can rotate the bones if you need to so that th Z axis are all aligned.

<img src="../images/DEV-01/DEV-01-C1.png" width="1100"/>

    Cleaned up bone rotations

<img src="../images/DEV-01/DEV-01-C3.png" width="1100"/>

    This is what it looks like in humans

<img src="../images/DEV-01/DEV-01-C2.png" width="1100"/>

    Be sure to clear the parenting using Alt P

<img src="../images/DEV-01/DEV-01-C4.png" width="1100"/>

    Rename the constraint bone

<img src="../images/DEV-01/DEV-01-C5.png" width="1100"/>

    Shift click IK_Front.L and then FrontUpperLeg.L an then F2 to find inverse kinematics

<img src="../images/DEV-01/DEV-01-C6.png" width="1100"/>

    Applied

<img src="../images/DEV-01/DEV-01-C7.png" width="1100"/>

    This is what it looks like in humans

<img src="../images/DEV-01/DEV-01-C8.png" width="1100"/>
    
    Set chain length to 1 in metagross since it doesn't have too many limbs

<img src="../images/DEV-01/DEV-01-C9.png" width="1100"/>
    
    For humans however, since theres more joints, we would likely want a chain length of 2

<img src="../images/DEV-01/DEV-01-C10.png" width="1100"/>
    
    Next we will want to lock the Y axis on metagross, given the behavior of how its legs move

<img src="../images/DEV-01/DEV-01-C11.png" width="1100"/>

    For humans, we would lock both the Y and Z axis

<img src="../images/DEV-01/DEV-01-C12.png" width="1100"/>

    In pose mode, if you click on the left hand gizmo, and then select Local, you should see the directions that each axis influences

<img src="../images/DEV-01/DEV-01-C13.png" width="1100"/>

    Extrude Bone, fix rotations, clear parent, and move down along z in metagross. This bone is so that the joint does not reverse itself.
    Poles are used to help blender to understand which way a joint should be rotating

<img src="../images/DEV-01/DEV-01-C14.png" width="1100"/>

    Extrude Bone, fix rotations, clear parent, and move down along y in human

<img src="../images/DEV-01/DEV-01-C15.png" width="1100"/>

    What this bone is meant to prevent:

<img src="../images/DEV-01/DEV-01-C16.png" width="1100"/>

## Working with Poles

    Select the yellow bone and add armature in the setting

<img src="../images/DEV-01/DEV-01-D1.png" width="1100"/>

    Apply the pole we just made. it will cause it to turn 90 degrees

<img src="../images/DEV-01/DEV-01-D2.png" width="1100"/>

    Turn it back 90

<img src="../images/DEV-01/DEV-01-D3.png" width="1100"/>

    Parent the Pole to the IK control

## Apply to other legs

    Add the IK system to the back left leg

<img src="../images/DEV-01/DEV-01-E1.png" width="1100"/>

    "Symmetrize"

<img src="../images/DEV-01/DEV-01-E2.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-E3.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-E4.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-E5.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-E6.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-E7.png" width="1100"/>
<img src="../images/DEV-01/DEV-01-E8.png" width="1100"/>

## End Result

[![Ch1](https://img.youtube.com/vi/Yw1J03ssUtQ/0.jpg)](https://www.youtube.com/watch?v=Yw1J03ssUtQ)


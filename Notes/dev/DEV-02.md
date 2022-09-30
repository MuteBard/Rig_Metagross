# DEV-02, Ch2 Alternate way to rig using the Rigify Workflow 
### Link:[<>]
#### Tags: []


## Applying the rigify workflow

    Install rigify

<img src="../images/DEV-02/DEV-02-A1.png" width="1100"/>

    AutoRun Python Scripts

<img src="../images/DEV-02/DEV-02-A2.png" width="1100"/>

    First create a singular bone. I will later delete this bone in edit mode to free up the armature.
    Then I will add the pre made rigify bones in its place

<img src="../images/DEV-02/DEV-02-A3.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A4.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A5.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A6.png" width="1100"/>

    Added

<img src="../images/DEV-02/DEV-02-A7.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A8.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A9.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A10.png" width="1100"/>

    Before you click  Re-Generate Rig, make sure you did not make any modifications to the bone counts of the sample rig.
    I had and needed to add a tiny stub to make it happy on each of the legs.

<img src="../images/DEV-02/DEV-02-A11.png" width="1100"/>

    Select Re-Generate the Rig

<img src="../images/DEV-02/DEV-02-A12.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A13.png" width="1100"/>

    I will do automatic weights for now, but I will tweak them later. Metagross is a robotic, inorganic creature and only some parts should be influenced while none should be at all. Automatic weights disregards this in a way and makes the ring around Metagross bend in a way that not
    natural for it. So in the next topic, ill visit weight painting so that I can rig this better.

<img src="../images/DEV-02/DEV-02-A14.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A15.png" width="1100"/>

## Topic B

    Make sure there are no textures, get a white color for clear visibility of weights. 
    For now I unparented the rig from the mesh

<img src="../images/DEV-02/DEV-02-B1.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-B2.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-B3.png" width="1100"/>

    Then I cleaned up the vertex groups by deleting all of them, (There was some lingering vertex groups from a prior parenting).
    Then I reparented the ring to the mesh using automatic weight. 

<img src="../images/DEV-02/DEV-02-B4.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-B5.png" width="1100"/>

## Topic C

    If you you go to the vertex groups in edit mode, we find out how much influence
    certain bones have on the mesh. SOme of them are over extending like the upper legs, They should not bleed into the metagross head. We will set the weights for this bone to 0

<img src="../images/DEV-02/DEV-02-C1.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C2.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C3.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C4.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C5.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C6.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C7.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C8.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C9.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C10.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C11.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C12.png" width="1100"/>

    Rig revised

<img src="../images/DEV-02/DEV-02-C13.png" width="1100"/>

## End Result

[![Ch2](https://img.youtube.com/vi/fgaM7EPIV68/0.jpg)](https://www.youtube.com/watch?v=fgaM7EPIV68)

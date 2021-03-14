# CogniFly-STL
3D files (STL) for printing and assembling current and past versions of CogniFly

![CogniFly](imgs/CogniFly.jpg "CogniFly")


![Fold as you assemble](imgs/folding_as_you_assemble.png "Fold as you assemble")


![Squeeze and fit](imgs/squeeze_and_fit.jpg "Squeeze and fit")

![Squeeze and fit 2](imgs/snap-fit.jpg "Squeeze and fit 2")
It's a very snug fit! You need to squeeze the round tube-like side, but without damaging it. Probably the hardest part to assemble.

![All parts together as they should be printed](Latest/CogniFly_All_Parts.png "All parts together as they should be printed")
The only part that needs support to be printed is the [Battery_holder_magnetic_lid.stl](Latest/Battery_holder_magnetic_lid.stl). Depending on your printer, settings, fillament, etc. some holes will change the internal diameter and they may be too loose. In this case, you will need to glue the struts (carbon fiber or bamboo skewers) or, instead of absorbing the impact, the frame will just fall apart and almost no impact energy will be absorbed by the flexible parts. If you get a nice snug-fit between the struts and the TPU parts, you will not need to glue them together. In the case of bamboo, because they break much more easily than carbon fiber (never managed to break any!), if you glue them it will be annoying to replace.


![Render](imgs/Perspective.png "Render")
All the parts in red are made of flexible TPU 95A. 

![FC and ESC](imgs/Right.png "FC and ESC")
Flight controller and ESC (4-in-1) are mounted between the battery and the central part of the frame (the empty space seeing above). The central was designed with 20x20mm mounting holes. The motors shown in the photograph at the top are 1104 ones and the holes are for M2, but be careful with the length of your screws so you don't destroy the motor windings!

## Finally, this is a collision *resilient* design, but it has its physical limits as everything else in life. It will absorb a lot of energy even in the case where it flex so much that you manage to hit the internal electronics agains the obstacle, but in this case it may damage something that is fragile. We used poly carbonate propellers and they lasted quite a few crashes before becoming too damaged for flying :)


**For more details, check [thecognifly.github.io](https://thecognifly.github.io/).**

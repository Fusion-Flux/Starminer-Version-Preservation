━━━━━━━━━━━━━━━━━━━━━━━━
    StarMinerMod 0.9.7 For Minecraft1.7.10(&Forge)
    By：ARUBE
━━━━━━━━━━━━━━━━━━━━━━━━


Thanks for downloading StarMinerMod.

This mod needs Minecraft1.6.x or 1.7.10 with Forge in order to install&use.
Just put jar to your mod folder and you are ready for all.
 Starminer162-X_X_X：for 1.6.2
 Starminer164-X_X_X：for 1.6.4
 Starminer1710-X_X_X：for 1.7.10
(Do not put all jar in. Just correct one jar for your version.)

This mod is still in working progress.
So be careful to use it on your mc world, cause it can mess up your wonderful world.
I strongly suggest you to use this mod on your bran new mc world.
Please do not redistribute this mod. Thanks for reading. Have fun.


[0.9.7changelog]
 -[!important for v0.9.6 users]Some recipies has changed!!
  (Gravity wall is now made from stardust. And stardust can be made from OuterStarCore)
 -Upgraded Minecraft&Forge version to 1.7.10.
 -Added G-rappleGun.
 -Added FakeRotator.
 -Added Chest(+G).
 -Added Arrow(+G).
 -Added Floating Block Gun.
 -Added stardust as intermediate material.(And changed few recipes.)
 -Added more flower&sapling(+G).
 -Fixed some bugs.


[0.9.6changelog]
 -Changed the teleporting way for GOrbit dimetion.
  Player needs to have red arrowed "GravityController" in order to teleport.
 -Lowered the height of border when teleporting to GOrbit dimetion.(before:y256+64  now:y256+32)
 -Added Item "Starbed".
 -Enabled sleep-till-morning in GOrbit dimention.(Only on single player mode)
 -Chanded rendering for fluid in GOrbit dimention.
 -Fixed "gravity freeze" symptom of other player.
 -Fixed some hardness of block.
 -Fixed lack of translation in GravityCoreBlock GUI.
 -Fixed some conflict with other MODS.



=======About GravityCoreBlock=======

GravityCoreBlock is placed as core of star, which is auto-generated in world.
And also, you are able to craft it, and create your own star(or cylinder type space colony).
When you are to make your own, you need to know about "star type".
Type can be chanded pressing top right button of GravityCoreBlock GUI.

Here are descriptions about each type.
 [sph(sphre type)]
   Generates sphere type gravity field.
   When terraform, It makes sphere shape.
 [cub(cubic type)]
   Generates cubic type gravity field.
   No terraform for this type.
 [xCyl,yCyl,zCyl(xyz-cylinder type)]
   Generates cylinder type repulsive field.
   When terraform, It makes cylinder shape.


So, what's Terraform?

It's a function of GravityCoreBlock helps making your own star.
First, you need to set a "star type" as I wrote above.
Second, you need to set star size(as "StarRad" in GUI, which means radius of star).
Last, place some blocks to "TerraformingMaterials" inventory.
After all is done, GravityCoreBlock starts to make a shape from y-high to y-low,
using blocks in "TerraformingMaterials" inventory.
It takes a while for small star, takes long time for bigger one.
When you need to stop function, just displace block from "TerraformingMaterials" inventory.
When you need to reset TF work, change either type or size of GravityCoreBlock.


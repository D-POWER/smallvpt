smallvpt
========

<b>smallvpt</b> (small volumetric path tracer) is an extension of <a href="http://www.kevinbeason.com/smallpt/">smallpt</a>, which is a tiny path tracer written by Kevin Beason in less than 100 lines of code.

It currently includes basic volumetric light transport supporting multiple scattering and homogeneous media. Medium is defined as a sphere surrounding the scene, with parameters sigma_s and sigma_a to control the scattering and absorption of light.

Here is a render of a Cornell Box filled with a homogeneous medium:

![My image](https://raw.github.com/D-POWER/smallvpt/master/Renders/image%20-%200.01%20sigma_s%20%5B2048spp%5D.png)

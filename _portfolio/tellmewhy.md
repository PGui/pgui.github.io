---
title: "Tell Me Why"
author_profile: true
excerpt: "Tell Me Why 👫 is an other narrative game developed by Dontnod Entertainment."
order: 999
header:
  teaser: /assets/images/projects/tellmewhy/teaser_tellmewhy.jpg
gallery:
  - url: /assets/images/projects/tellmewhy/tellme1.png
    image_path: assets/images/projects/tellmewhy/tellme1.png
  - url: /assets/images/projects/tellmewhy/tellme2.png
    image_path: assets/images/projects/tellmewhy/tellme2.png
  - url: /assets/images/projects/tellmewhy/tellme3.png
    image_path: assets/images/projects/tellmewhy/tellme3.png
  - url: /assets/images/projects/tellmewhy/tellme4.png
    image_path: assets/images/projects/tellmewhy/tellme4.png
  - url: /assets/images/projects/tellmewhy/tellme5.png
    image_path: assets/images/projects/tellmewhy/tellme5.png
  - url: /assets/images/projects/tellmewhy/tellme6.png
    image_path: assets/images/projects/tellmewhy/tellme6.png
---
{: .text-justify}
Tell Me Why 👫 is an other narrative game developed by Dontnod Entertainment and edited by Microsoft. It will be available on PC and Xbox One.

In this intimate thriller, reunited twins Tyler and Alyson Ronan use their special bond to unravel mysteries of their loving but troubled childhood.

{% include video id="JVXqGQC9J2o" provider="youtube" %}

## What I did on this project

{: .text-justify}
For this project, we decided to change the animation pipeline and use Maya instead of Motionbuilder because it offered more advantages.
So, we ported everything [I did](https://guillaumepastor.com/portfolio/captainspirit/#what-i-did-on-this-project) to Maya and provided a new set of tools for the animators to work in the best possible conditions.

{: .text-justify}
I also work on one major step to improve the Dontnod's asset pipeline : **GAIA** aka **"The Derusher"**.

{: .text-justify}
**"The Derusher"** aims to provide a user friendly way to list and create assets within the engine with their sources (meshes, textures, materials) with the right naming and the right location using **3DSMax**, **Maya**, **Unreal Engine Python**. The goal is to prevent errors from artists when creating and naming assets in the editor and have a better control on how are created these assets.

{: .text-justify}
In fact were was different derushers, one for each job category:

* **Props Derusher** : List the meshes needed for the game and create the uassets (Static/Skeletal Meshes, Materials, Textures) and the associated source files within perforce (.max, .ma, .fbx, .png, .psd, .sbs...)
* **Characters Derusher** : Exactly like the Props derusher but taking into account some character department specificities
* **Animation Derusher** : Retrieve assets from the Props and the Character Derushers to create working scenes for the animators

## Gallery

{% include gallery %}

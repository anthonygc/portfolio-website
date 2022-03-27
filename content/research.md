+++
title = "Research"
slug = "research"
+++

## Research & Tutorials

### Merging the Gap

The GANS model is an Artifical Neural Network (ANN) that is able generate models that are similar to that of the training data set. The GANS model stands for "Generative Adversarial Networks". There is a noticeable gap that is present within this model and tools sucha as blender. Blender is capable of running plugins that are user made. It would be interesting to utilize the ability to write and understand the GANS model within Blender. Thus, I would like to answer, in what way can a GANS model be used for 3D Generation of models within Blender.

Broadly speaking, below are some steps I intend on using (however, this is subject to change):

  - Create one reference model.
  - Generate more that is randomized in color and/ or texture
  - Learn more about the improvised model for GANS model and come up with an idea on how to abstract binary information on 3D object
  - Use the info as training set.
  - After completed trial, program a system that would automate the steps above.

### About

Describe the software resource and explain its relevance to your topic. Please include the link to the software resource.

- There will be two software's that I will be utilizing for my research. This will include Blender and Unreal engine. This will be relevant to my topic of interest due to the fact that I am able create 3D graphics and creations whilst also programming plugins for these engines. Because of this ability to program within each engine, I am able to create artificial intelligence models and see each algorithm work visually.

[Blender](https://www.blender.org/)
[UnrealEngine](https://www.unrealengine.com/en-US/unreal?utm_source=GoogleSearch&utm_medium=Performance&utm_campaign=an*3Q_pr*UnrealEngine_ct*Search_pl*Brand_co*US_cr*exact&utm_id=15913918750&sub_campaign=&utm_content=existing&utm_term=unreal%20engine)

---

### Features

Outline the main features of the software. Why is this software necessary for your work?

 -**Blender**
    - Blender is a 3D modeling software but is also used for video editing, VFX creation, and sculpting. You are able to also install plugins or make your own plugins. It has a python API built into the software so that you are able to make these plugins. These plugins are also known as "Addons". My end goal with this software is to make generative machine learning modules that can be used within blender.

 -**Unreal Engine**
    - Unreal engine is another general creation tool. This has numerous applications as it is used in game development, film, and prototyping. This can also be used for modeling and texturing. Its core language is C++, but it uses functional nodes as well for programming tasks. AI can also be implemented into Unreal engine. My goal with this is to import models from blender into Unreal. I will then try to implement sound visualization by programming particles to move based on frequency. I would like to create some sort of experience using Virtual Reality Hardware.

---

### Obtaining the resource

Where do you find this software resource? Is it an open source project? an online tool? How do you install it? Are there any libraries that are also necessary to install?

**Blender**

- I have found Blender a while back. I actually started using Blender back in 2020 during the summer of the pandemic. I really became interested in 3D modeling and the platform itself by using Virtual Reality hardware. Blender is an open source software and has extensive documentation and online tutorials. This is of course, an online tool that can be installed via the official website. This can be used in linux, mac, and windows. No libraries are needed for the installation.

**Unreal Engine**

- Unreal engine is a platform I am not too fluent in. But I am determined to learn it. Unreal engine is, however, a closed source software. But this software is free to use for personal projects. There is a fee when getting a certain amount of income on your projects. This is an online tool that can also be installed via the official website. No libraries are needed for the installation of the software. Libraries are optional during development while using the software.

---

### Setup

Include steps of all necessary steps to get the software to run (for example, installations). Include the commands to run if necessary.

- **Blender**

For Blender the installation and set-up is quite simple. There is no need to install any extra libraries or anything else of that matter. Scripting can be done within Blender's application. It would, however, be interesting to se if I can hook up an IDE with blender and see if it could update in real time. I have included the steps below.

- Step 1: Navigate to the blender website. The link to the website can be found [here](https://www.blender.org/).

- Step 2: Press `Download Blender`

- Step 3: Once you have pressed this button, you will see a large light blue button which says `Download Blender` with the version next to it. While writing this, the latest version at the time is 3.0.1. If you wanted to install a previous version of the application, you could navigate to the `previous version` box at the top of the website. Although, all previoous versions that are being maintained are located at the top left of the screen. This will say `Long-term Support`.

- Step 4: Once you have pressed this button, press yes or okay for every page that is prompted to you (unless you want it to be installed on another drive).

- Step 5: You have successfully installed blender!

- **Unreal Engine**

The unreal engine installation is similar to that of the blender installation. Although, there are a couple of ways to do this. For example, you could download Unreal engine and any of its versions within the main website. However, you can install a hub called `epic games` where you can view tutorials for the engine and also download any versions of the engine. I will provide the steps below.

- Step 1: Navigate to the epic games website. You can find the website by clicking [here](https://www.epicgames.com/store/en-US/)

- Step 2: You will likely encounter a lot of games on this website. I do have a passion for games. However, for the sake of this project, we will ignore them. However, in order to download anything within the epic games application, you will need to make an account. Press sign in at the top right of the screen.

- Step 4: You will see a menu which says `sign in with an Epic Games Account`. At the bottom of this menu, you should see `Don't have an Epic Games Account? Sign Up`. From here, you should input your credentials.

- Step 5: Once you are all signed up, click download at the top right of the screen.

- Step 6: You will be prompted to a couple of screens depending on what your operating system is. Press yes or okay for the pop-up menus unless you want this to be installed on a different drive.

- Step 7: Once you have installed Epic Games, you need to sign in using the credentials that you used to sign up. This will likely include your username and password.

- Step 8: Go to the unreal engine section of epic games which is located on the left of the application. Once you have navigated to this section click download UE5. This version is in beta. However, it has a lot of interesting new features that could be utilized depending on what your focus is for development. For this project, I will likely download the latest version of unreal engine four.

- Step 9: Once you have pressed this version, you will be prompted to a different menu which says `Choose installation location`. From here you can choose where you want unreal engine to be installed.

- Step 10: The application for unreal engine will appear in your library as it is downloading. A shortcut to the application will also be available within your desktop.

---

### Execution

How do you get the resource ready to use? Are there inputs to know? Please show a step-by-step guide (in a tutorial format) for readying the resource for your work. Include screenshots of successful execution and use of the software.

- You don't need any extra resources or other steps to "prepare the software". However, if you want dependencies of any kind within Blender. You can navigate to the add-ons section. I will provide the steps below.

- Step 1: Within the Blender viewport, at the top right, you should see `edit` section. Click this and scroll down to `preferences`

![image of edit section](graphics/edit.png "image of edit section")

![image of preferences section](graphics/pref.png "image of preferences section")

- Step 2: Once you have navigated clicked on the preferences tab, navigate to the addons section of the menu. From here you are given the choice to install any addon that has been published.

![image of addons section](graphics/addons.png "image of addons section")

- It should also be noted that we will be scripting from within blender. We can write scripts for making our own addons. To do this we have to navigate to the `Scripting` tab which can be seen at the top right of the blender viewport.

![image of scripting section](graphics/scripting.png "image of scripting section")
![image of scripting_menu section](graphics/scripting_menu.png "image of scripting_menu section")

---

### Helpful resources

Include some of the relevant resources (links, articles, etc.) that you used to write in your tutorial.

- Listed below is a list of documentation and helpful resources.

**Blender**

- [Blender Documentation](https://docs.blender.org/)

- [Blender Tutorials](https://www.blender.org/support/tutorials/)

- [Best Tutorials of 2022](https://all3dp.com/2/best-blender-tutorials/)

**Unreal Engine**

- [Learn Unreal Engine](https://www.unrealengine.com/en-US/learn)

- [Unreal Engine Documentation](https://docs.unrealengine.com/4.27/en-US/)

- [Free Unreal engine tutorials](https://www.udemy.com/topic/unreal-engine/free/)

---

(Did you remember to add your name and GitHub account name and date to the top of this document?)

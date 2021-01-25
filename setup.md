---
layout: page
title: Setup COSMOS 2.0
---

# How to Setup COSMOS 2.0:

> ## Software
>
> For this lesson you will need to make a request for **COSMOS 2.0** download link 
> from the Social Data Science Lab website. 
> [ESRC COSMOS 2.0 Open Data Analytics Software](http://socialdatalab.net/COSMOS).
> **Download** the program files on your machine by clicking the link you have sent.
>
> Note: this is a Java program that runs on your machine (not in the cloud). It runs inside your browser, but no web connection is needed.
>
{: .prereq}

## Mac


### There are two ways to start COSMOS:

#### 1. Starting COSMOS as an application
- Double clicking the *COSMOS-Installer.dmg* and drag the COSMOS icon over the *Applications* shortcut icon. This will copy COSMOS into your Applications folder.
-  Instead of double-clicking the COSMOS application, right-click (Control-click) the file and select Open from the context menu. See the illustration
below.
![Parse Options](fig/Open_COSMOS.png){:height="300px" width="500px"}
- A confirmation dialog warns about unverified developer. In the dialog, click on
*Open* button.
- As soon as you click *Open* button, a black pop-up window(Terminal) appears on the screen for **COSMOS self-check**. (Checkout the COSMOS self-check section below.)
![Parse Options](fig/Cosmos-self-check.png){:height="300px" width="500px"}

 
**Note:** Later on, you may launch COSMOS the way you normally start applications.


#### 2. Starting COSMOS via a script from Finder
- Once you have downloaded the COSMOS package (the file name extension is tgz, tar.gz, or tar), double click the file in Finder and it will be automatically extracted.
- When you are about to run Start COSMOS.command for the first time, follow these steps as illustrated below:
    1. Right-click (Control-click) the file and select Open from the context menu.
    ![Parse Options](fig/Start_with_script.png){:height="300px" width="500px"}
    2. A confirmation dialog warns about unverified developer. In the dialog, click on **Open** and COSMOS will launch.
    ![Parse Options](fig/Verify_developer.png){:height="300px" width="500px"}
    **Note:** you may launch COSMOS by simply double-clicking the Start COSMOS.command file in Finder. The permission to open it needs to be granted only once.

#### 3. COSMOS Self-check:
- When you start COSMOS for the first time, a self-check is run to ensure that COSMOS runs correctly. 
- First of all, you need to press 'Enter' to begin the check as you inform on the Terminal window. 
- There are **three** steps in this self-check. 
    
**Step 1:** Trying to run MongoDB.

![Parse Options](fig/Mongo.png){:height="300px" width="500px"}

**Step 2:** Trying to run Java.

![Parse Options](fig/Java.png){:height="300px" width="500px"}

**Step 3:**  Trying to run Network Node Centrality calculator.

![Mac](fig/centrality-mac.png){:height="200px" width="500px"}


- For each step you will ask whether you saw a  warning. If you did, the self-check will exit and you are presented with a Finder window open in the corresponding folder of the file. In the Finder window, right-click (Control-click) on the file, and from the context menu, select **Open** . See the illustrations below. 

- After clicking Open from the context menu, you will receive a similar warning as before about unverified developer, but this time the dialog has an Open button. Click it: this will grant permission to open the file also in the future.

- Then your internet browser will open automatically and COSMOS will run on your machine locally.

- The self-check is only run the first time you start COSMOS. After that, everything is set up correctly and COSMOS will run directly when you start it.

> ## Warning!
> - When COSMOS is running, please do not close the terminal window. 
> - To exit COSMOS, please press 'CTRL+C'.
> - If you close Terminal window without pressing CTRL+C, the next time you try to run COSMOS, it will raise an error. See illustration below.
> ![Parse Options](/fig/Error.png){:height="250px" width="450px"}
> - To solve this issue, press 'Enter' and CTRL+C to stop it.
>
{: .prereq}
 
 


{% include links.md %}

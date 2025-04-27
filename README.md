# cs2261-lab-0-mac-installation-solved
**TO GET THIS SOLUTION VISIT:** [CS2261 Lab 0-Mac Installation Solved](https://www.ankitcodinghub.com/product/cs2261-lab-00-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121035&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2261 Lab 0-Mac Installation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Mac Installation

Provided Files, Folders, and Executables

● .vscode (folder)

● tasks.json

● Makefile

● main.c

● Dockerfile

● mGBA.app

Files to Edit

● tasks.json

Instructions

Part 1: Docker Desktop

First, you’ll need to download Docker Desktop. In order to do this, you’ll need to sign up for Docker Hub. Sign up for Docker Hub here: https://hub.docker.com/signup. You can use your personal or GT email; either is fine.

Once you’ve signed up, follow the detailed Docker Desktop download instructions here: https://docs.docker.com/docker-for-mac/install/

When you see the following, click on the correct download button depending on which Mac you have (Intel or Apple chip, as seen above) and, granted you’re logged into the Docker Hub account you created, your download will begin.

In your downloads, you’ll see “Docker.dmg”.

Now, follow the “Install and run Docker Desktop on Mac” instructions on the Docker Desktop download instructions page. Stop once you reach the “Uninstall Docker Desktop” section. Great, you’ve got Docker Desktop on your machine! 🙂

Go to your applications, and click Docker.app.

In the menu bar (top right of your screen), you should see a little icon that looks like the following:

This icon indicates that Docker Desktop is running on your machine (status is shown when you click on it)! YOU MUST BE RUNNING DOCKER IN ORDER TO BUILD YOUR CODE. Otherwise, when you attempt to build your code, you will see the following error:

If you see this in the future, you’ll know you forgot to open the Docker Desktop application.

IMPORTANT: Please, avoid updating Docker Desktop at all costs! Sometimes updates lead to some things on the backend breaking, so unless you really have to perform an update, it would be best to not.

Part 2: mGBA

Let’s get the GBA emulator setup! mGBA is the emulator for this class. If you already have a GBA emulator that you are comfortable with, I still highly recommend you use this one for 2261 projects.

It has some special features that will come in handy for debugging.

Find the mGBA application in the Lab00 folder. I recommend creating a parent CS2261 folder that will contain all of your homework, labs, etc. and keeping “mGBA.app” in this folder. Lab00 should be in this CS2261 folder, too. Keep a note of the exact path to “mGBA.app”. In the image below, you’ll see a recommended folder setup. The exact path to the application, in my case, is /Users/julia/Desktop/ta2261/mGBA.app

You can verify the directory location of the “mGBA.app” on your machine by simply opening

Finder, opening the CS2261 folder where you placed the “mGBA.app”, and dragging the

“mGBA.app” icon into the terminal. The output in the terminal is the exact path to the “mGBA.app”.

Another way to verify the directory location is to open the folder in Finder, right-clicking the

“mGBA.app” icon, and pressing the option key on your keyboard. Pressing the option key changes the “Copy” option on the dropdown menu to “Copy “mGBA.app” as Pathname”. Once you have done that, you can paste (cmd+V) anywhere to see the directory location of the emulator.

In my case, as stated before, the exact path is /Users/julia/Desktop/ta2261/mGBA.app. Copy this exact path and paste it into your tasks.json, on line 9 in between “open” and “./Project.gba”. Make sure there is a space after “open” and before “./Project.gba”. The (truncated) image below outlines what my tasks.json looks like. Your exact path on line 9 will be different! Remember to save your changes to your tasks.json file.

Once mGBA is in the correct folder in your machine, make sure that you can open it – double click on it. The application should open, showing a black screen since we did not load any ROMs into it. If instead you get an error that says you cannot open the mGBA app, or it just doesn’t open at all, follow the instructions here to allow your Mac to open the application from an unidentified developer: https://support.apple.com/en-gb/guide/mac-help/mh40616/mac. Then, opening the app again.

Part 3: Visual Studio Code

Visual Studio Code is the text editor of choice for this class. We highly recommend you use this editor. If you do not already have VSCode, you can download it here: https://code.visualstudio.com/download.

Once downloaded, open VSCode, and open the Lab00 folder by selecting File &gt; Open &gt; Lab00.

Open main.c and then hit cmd+shift+B to build your project (remember, Docker Desktop needs to be running!). This first compilation process will take some time because a Docker image is being downloaded from Dockerhub (don’t worry about the nitty gritty details of this). All subsequent builds will not take this long (whew). In the terminal output in VSCode, you should see something like this for the very first time you build:

Once the build is complete, you should see something like the following pop up:

If instead you get an error that says you cannot open the mGBA app, or it just doesn’t open at all, follow the instructions here to allow your Mac to open the application from an unidentified developer: https://support.apple.com/en-gb/guide/mac-help/mh40616/mac. Then, try building again. You should see the image above.

Submission Instructions

Zip up the entire sample project folder, including all source files, the Makefile, and everything produced during compilation (including the .gba file and your tasks.json in the .vscode folder). Submit this zip on Canvas.

It is your responsibility to ensure that the file you submitted on Canvas includes all the files required. Name your submission Lab00_LastnameFirstname, for example:

Lab00_ReuterJulia.zip

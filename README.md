# Git_Github_Workshop_Fall_2022


<img src="https://i.imgur.com/JybZuXd.png" alt="drawing" width="100"/> <img src="https://i.imgur.com/Bzkqs5I.png" alt="drawing" width="100"/>

<!-- Template of how emails should look like before we send them out. Make sure you get the "go" from the Secretary or President before we send out the emails to all club members -->

# Computer Science Society Club


## Git and Github Demo

Date: Septembery 27th, 2022 <br>
Zoom recording: [TBD]() <br>
Git Commands [Cheat Sheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf) <br>
Learn Git through a [Youtube Video](https://www.youtube.com/watch?v=tRZGeaHPoaw) <br>

### Installing Git
1. Install [Git](https://git-scm.com/downloads) if it's not already download on your operating system.
  --For Mac users, it should already come pre-installed
  --For Window users, check out this [link](https://www.computerhope.com/issues/ch001927.htm) to learn how to install Git
2. Check that you've installed Git properly. Open up your terminal and run the command `git --version`. If your terminal outputs your git version, then you are good to go, if not `retry doing` the first step.
  <img width="394" alt="Screen Shot 2022-09-24 at 12 35 07 PM" src="https://user-images.githubusercontent.com/71786791/192108981-521a2fbe-b643-4276-af8a-eb1db9db75ac.png">

### Adding Git Username
1. Make a [GitHub](https://github.com/) account.
2. Open up your terminal (command line)
3. To add a username to git enter this command `git config --global user.name "Mona Lisa"`. **Note: Your username doesn't have to be the same username as your GitHub account**

-----> You can change the name that is associated with your Git commits using the git config command. The new name you set will be visible in any future commits you push to GitHub from the command line. If you'd like to keep your real name private, you can use any text as your Git username.

4. Confirm you have set the username with the command `git config --global user.name`. If you did everything currently you should have an output of the username you just created.
<img width="467" alt="Screen Shot 2022-09-25 at 9 23 12 PM" src="https://user-images.githubusercontent.com/71786791/192176275-3148d1d5-5ddb-4257-b1eb-7438929b5a85.png">

### Adding GitHub/Git Email (Important)
1. If you haven't already, let's add an email to your Github account. Head over to GitHub and let's head to `Settings`.
<img width="222" alt="Screen Shot 2022-09-25 at 9 35 14 PM" src="https://user-images.githubusercontent.com/71786791/192177171-c5efff88-1eee-43a4-a65a-a32bd077cb84.png">
2. On the left side, under the `Access` section, click on `Emails`.
<img width="296" alt="Screen Shot 2022-09-25 at 9 36 30 PM" src="https://user-images.githubusercontent.com/71786791/192177295-506aefdb-0779-46e6-9afa-6b7622c8d191.png">
3. Under `Add Email Address`, add your email address that you want to use.
<img width="355" alt="Screen Shot 2022-09-25 at 9 39 32 PM" src="https://user-images.githubusercontent.com/71786791/192177514-7d7843f9-5fac-4b53-a26a-1337c91ccb32.png">
4. After you add your primary email, you will need to `verify your email address (important)`. Take a few minutes to verify your email. Github will send you an email, and you'll need to click the link that they sent you and you should see a message like below:
<img width="522" alt="Screen Shot 2022-09-25 at 9 42 06 PM" src="https://user-images.githubusercontent.com/71786791/192177749-69bb25de-95b0-4e93-a843-28bc7e4d1b5e.png">
5. Next, under `Primary email address", select the email that you just listed and click `Save`.
<img width="779" alt="Screen Shot 2022-09-25 at 9 43 43 PM" src="https://user-images.githubusercontent.com/71786791/192177983-fd1efd8a-ff76-4c99-b881-7a10742b5430.png">
6. Scroll down a little bit and make sure this is checked:
<img width="777" alt="Screen Shot 2022-09-25 at 9 47 07 PM" src="https://user-images.githubusercontent.com/71786791/192178183-8bbe53f2-ff03-4764-9aa5-cfc045d6570f.png">
7. This is how you connect your email to GitHub. Now, let's connect your email to your Git (command - line). <br>
8. (Important) Open up your terminal and enter the command `git config --global user.email "email@example.com"`. Enter the same email that you made as your primary email on GitHub. <br>
9. Double check that your email was added properly with the command `git config --global user.email`.
<img width="461" alt="Screen Shot 2022-09-25 at 9 50 30 PM" src="https://user-images.githubusercontent.com/71786791/192178458-8b6a9b72-47fc-426f-8eee-8cd6fece6df3.png">
10. You're all set!

### Making default branch Main
1. Open up your terminal and enter the command `git config --global init.default branch main`
-----> Good practice to name your default branch `main` as GitHub recommends we name it this, rather than the default name `master`.

### Connecting IDE to Github using Git
1. Download an IDE of your preference. We'll be using [Visual Studio Code](https://code.visualstudio.com/download) for the demo. Please download VSC if you don't have it already.
2. Open up Visual Studio Code.
3. Let's create a new Folder that will contain our new files. Click on `Open Folder`.
<img width="385" alt="Screen Shot 2022-09-25 at 10 15 45 PM" src="https://user-images.githubusercontent.com/71786791/192180829-a0da7a52-c675-435c-b16f-9e0e77362069.png">
4. Choose where you want to save your folder. Then, click on `New Folder`. Give the folder any name and then `Open`. The folder.
<img width="260" alt="Screen Shot 2022-09-25 at 10 17 14 PM" src="https://user-images.githubusercontent.com/71786791/192181092-4989820f-8cd0-4ba2-9e5f-38531d65615a.png">
5. You should now have a new folder inside of Visual Studio Code
<img width="925" alt="Screen Shot 2022-09-25 at 10 20 37 PM" src="https://user-images.githubusercontent.com/71786791/192181282-834542ad-0b82-45e3-9756-2040dc20c256.png">
6. Head over to GitHub.com and let's create our first repository. <br>
7. At the top right corner, click on `New Repository`.
<img width="245" alt="Screen Shot 2022-09-25 at 10 11 32 PM" src="https://user-images.githubusercontent.com/71786791/192180487-d32f829e-66bf-4617-a479-8c0f6000d4c5.png">
8. Under `Repository Name` enter any name you want. A `Description` isn't necessary but up to you if you'd like to add it. Choose if you want to keep it public so others can see it or private so only you can access it. Next, click on `Create Repository`.
<img width="757" alt="Screen Shot 2022-09-25 at 10 24 24 PM" src="https://user-images.githubusercontent.com/71786791/192181777-fe4210cf-c4bf-40a9-8388-9380cf2a60a6.png">
9. You have now created a new repository. Now we will upload using all files we make in our Visual Studio Code folder to Github using Git.
10. Open up your terminal. Now let's try to access our Folder we created a few minutes ago in our terminal. To do this, we must first locate where we saved our folder. I saved it in on my `Desktop`. To access my `Desktop` using the terminal I can enter the command `cd desktop`. `cd` stands for "Change directory" and it basically takes you to that location in your mac. If you are unsure where you saved your folder, you can enter the command `cd `, but don't press enter yet. Open up your finder and search for your folder there. Once you locate it, drage the folder into your terminal. You should now see the path for where you folder is. Terminal does this automatically. 
<img width="323" alt="Screen Shot 2022-09-25 at 10 32 34 PM" src="https://user-images.githubusercontent.com/71786791/192182492-eef09e25-ef51-4d97-b5f4-c99319035e6e.png">
11. Once you know are inside where your folder is located (for me, it is desktop), enter the command `cd folder_name_goes_here`. After cd enter the folders name that we created in Visual Studio code. Now you are inside the folder that you created and soon once we add files, you'll be able to see them on your terminal.
<img width="399" alt="Screen Shot 2022-09-25 at 10 34 50 PM" src="https://user-images.githubusercontent.com/71786791/192182722-6298d937-a9cb-4c67-8c35-7377a75b1f49.png">
12. Inside of your terminal enter the command `git init`. This will create an empty repository "locally". <br>
13. Next, let's go back to the Github Repository, where we saw the commands that GitHub provided for us. Let's copy the command `git branch -M main' and let's paste it inside of our terminal and let's press enter. This will make our "official branch" and name it `main`.
<img width="805" alt="Screen Shot 2022-09-25 at 10 40 56 PM" src="https://user-images.githubusercontent.com/71786791/192183375-4d1f4222-5729-4b75-84f6-3e874b995b1d.png">
14. Next, copy the line below it, `git remote add origin git@github.com:r0m3c/Git_Practice.git`, and paste it in your terminal and press enter. Notice that after `github.com:` yours will be different because you have a different username and have a different name for your repository.
<img width="1500" alt="Screen Shot 2022-09-25 at 10 44 15 PM" src="https://user-images.githubusercontent.com/71786791/192183728-ae95fa5b-8901-4f98-9743-ae701e067fe6.png">
15. You are now ready to begin making changes to your folder in Visual Studio code!

### Using Commits/Push to upload changes to our Repository
1. Let's head over to Visual Studio code, where we made our new folder.
2. Let's create an `index.html` file and add some code.
<img width="1043" alt="Screen Shot 2022-09-25 at 10 53 01 PM" src="https://user-images.githubusercontent.com/71786791/192184653-eb4f779f-b758-4b89-9728-6104cbbfe8bb.png">
3. Now that we made these new changes to our folder, let's head over to our terminal and let's insert the command `git status`. Your terminal is now keeping track of any new code changes or files that you made. This tells us that we have new changes that we want to commit.
<img width="503" alt="Screen Shot 2022-09-25 at 10 54 47 PM" src="https://user-images.githubusercontent.com/71786791/192184971-d06fa79d-bf6c-4987-b640-5fc573a5b4d8.png">
4. In order to tell git that we want to upload these new changes to our repository, we can proceed in two ways. If you have made multiple files and you would like to upload all files that you made changes to you can enter the command `git add .' . If you enter the command `git status` again, you should now see that the files that were red are now green, meaning that everything in green will soon be uploaded to your repository. This adds all files in your folder to be uploaded. Now, let's say you made multiple changes, but you don't want to add all changes that you made to be uploaded. You can select a single file that you made a change to and enter it into the command line like this: `git add index.html`.
<img width="448" alt="Screen Shot 2022-09-25 at 11 08 17 PM" src="https://user-images.githubusercontent.com/71786791/192186273-d7ff2b30-1bb0-4e32-a712-6900bda65b58.png">
5. Next, we have to add a commit message to the files that we just added to be uploaded. We can do this with the command `git commit -m "add any message here"`. This message will appear in your Github repository when we push all changes in our next command.
<img width="565" alt="Screen Shot 2022-09-25 at 11 10 23 PM" src="https://user-images.githubusercontent.com/71786791/192186499-c9c166fd-5b1a-4715-bc44-24712b67be70.png">
6. Now, the final step to push all our changes that we made and send it to our Github repository is: `git push`. Your terminal should now give you a last command that you have to copy and enter into your terminal. Copy this command and press enter. <br>
7. Go to your Github Repository that we made. You should now see all files that we added and all changes, including the commit message in your repository.<br>
8. Practice some of these commands again.

### Creating Branches
1. Now, we will be creating a branch, which is basically a copy of your main branch where you will be able to add new features/new code without it affecting your main branch.
2. To make a new branch insert the command `git checkout -b nameHere`. You can name your branch whatever you want. This command creates a copy of your main.
<img width="507" alt="Screen Shot 2022-09-25 at 11 37 09 PM" src="https://user-images.githubusercontent.com/71786791/192189102-87edab3c-9cac-4db2-90ea-2e50b8046b27.png">
3. Insert the command `git branch`. You can now see all the branches you have in your git.
<img width="390" alt="Screen Shot 2022-09-25 at 11 38 05 PM" src="https://user-images.githubusercontent.com/71786791/192189193-051f9aba-16f1-4e18-8687-6403040d4884.png">
4. Next, let's add some code to compare the difference between what code we see in our current branch and our main branch. After you add new code to your Visual Studio code folder, let's add the new changes to be committed with the command `git add .` and let's give this commit a message with the command `git commit -m "new message"`. 
<img width="517" alt="Screen Shot 2022-09-25 at 11 41 01 PM" src="https://user-images.githubusercontent.com/71786791/192189443-f26d4a5f-29f7-4e9a-8c7e-4a815c1ccbd8.png">
5. Now let's go back to our main branch with the command `git checkout main`. Do you notice the different code? What is different?
6. Keep note that everything in our `main` branch is where our official code is stored.

### Creating Pull Requests
1. First, let's head back to the branch that we created with the command `git checkout nameHere`. If you forgot the name of your branch you can always enter the command `git branch` to see all your branches. 
<img width="484" alt="Screen Shot 2022-09-25 at 11 45 15 PM" src="https://user-images.githubusercontent.com/71786791/192189846-72a88e81-7d19-4fe3-b67f-021e66732842.png">
2. Next, let's add some new code again. Let's also add the changes and give it a message. <br>
3. Now, to push our branch that we just created along with our changes, let's enter the command `git push`. Our terminal will not tell us to copy the command it gives us and to enter that. Your command will differ from mine.
<img width="570" alt="Screen Shot 2022-09-25 at 11 53 59 PM" src="https://user-images.githubusercontent.com/71786791/192190731-8ad67864-07ea-4e73-b331-9c4753d4576e.png">
4. If we head back to our Github respository, we should now see something like this:
<img width="925" alt="Screen Shot 2022-09-25 at 11 54 51 PM" src="https://user-images.githubusercontent.com/71786791/192190793-076a4f17-ae5c-4237-92e5-ee2ca662d01b.png">
5. This means, that our pull request was successful. We aren't done yet, but to recap, what we have basically done so far is crated a new branch, added new code, pushed the changes and branch to our respository to create a pull request. <br>
6. Next, click on `open pull request` to open a pull request. In the next screen you can now see a screen where you can enter a title and description. Typically, if you're were working for a company, for the title you would write what you fixed and in the description you would enter a description of what your current code contains. Enter anything you want and then click on `create pull request`.
<img width="916" alt="Screen Shot 2022-09-25 at 11 59 23 PM" src="https://user-images.githubusercontent.com/71786791/192191180-2a667577-07ed-402e-8173-614f68cdf82a.png">
7. Take a second to explore the new page. You can see the code that you added. You can add reviewers if you want someone to review your code (if you were working on a project). Now, in order to merge the code in this new branch with the code in your main branch, click the `merge pull request` button and then click on `confirm merge`.
<img width="928" alt="Screen Shot 2022-09-26 at 12 02 41 AM" src="https://user-images.githubusercontent.com/71786791/192191475-0ca06f14-4611-4393-85a1-e25eed6683e0.png">
8. Now, go back to the `code` tab in your repository and take a look at your new changes that should show up in your files.
<img width="696" alt="Screen Shot 2022-09-26 at 12 04 18 AM" src="https://user-images.githubusercontent.com/71786791/192191697-1dacd277-c127-4a24-a712-f2c518bf508b.png">
9. This is how you create a new pull request and merge your changes with your main branch on Github. Now, if we want to see our changes in our main branch let's begin by going to terminal. <br>
10. Let's enter the command `git checkout main' to head back to our main branch. As you can see, the old code that we had previous to our new branch is showing. That is because our new changes are currently stored in our Github repository only. <br>
11. In order to bring the changes into Visual Studio code, we must enter the command 'git pull origin main'. Now, we can see the new changes inside of our new main branch. <br>
12. That is all! Practice creating a branch and pull request again.




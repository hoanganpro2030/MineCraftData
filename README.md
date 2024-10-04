# Minecraft data
Below is the instruction for update data while playing Minecraft

## Step 1
Install git, link download for windown here : https://git-scm.com/downloads/win <br>

Choose "64-bit Git for Windows Setup." <br>

After download complete, run the setup file and keep clicking "Next" til installable. 

## Step 2

Go to directory \.tlauncher\legacy\Minecraft\game\saves\ <br>

Right click and choose "Git Bash Here" <br>

Run this command in the bash:

> git clone

The data from MineCraftData should be downloaded to your computer.
After download completed, open game then enjoyed.

Above for the First time. In the next time you don't need to do those steps again but <b> remember </b> to run this command before playing:

> git pull

The pull command will update changes data from remote to your computer. If you forgot to run this command, a conflict maybe happens <br>

After playing, you want to update your change to everyone just do this <br>

Type the following instructions consequently :

> git add *
> git commit -m "Type everything you want here"
> git push

After push command is fired your changes will be uploaded to remote in a nutshell. Other people just run pull command to keep update with you.


### Authorized by : hoangankaitou

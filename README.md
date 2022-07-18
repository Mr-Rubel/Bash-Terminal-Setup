<h2 align="center">Make your Command line / Terminal more colourful to use it energetic</h2>

![Step 1](images/show.png)

## Start from here:

    sudo apt-get update -y && sudo apt-get upgrade -y

## Step 1:
Past this command on your terminal and Hit <kbd>Enter</kbd>

    bash -c "$(wget -qO- git.io/zsh.sh)"

## Step 2:
![Step 2](images/2.png)<br/>
No need to type anything, just Press <kbd>Enter</kbd>

## Step 3:
![Step 3](images/3.png)<br/>
Just Press <kbd>Enter</kbd>

## Step 4:
![Step 4](images/4.png)<br/>
Just Press <kbd>Enter</kbd>

## Step 5:
![Step 5](images/5.png)<br/>
Type your local computer password and Hit <kbd>Enter</kbd>

## Step 6:
![Step 6](images/6.png)<br/>
Again type your local computer password and Hit <kbd>Enter</kbd>

## Step 7:
![Step 7](images/7.png)<br/>
Just Press <kbd>Enter</kbd>

## Step 8:
![Step 8](images/8.png)<br/>
Now Choose the number of theme. In Mycase it's `171` number theme. After choose theme Hit <kbd>Enter</kbd>

## Step 9:
![Step 9](images/9.png)<br/>
Now just Press <kbd>q</kbd> from your Keyboard

## You're almost done!! after coming this stage
As you can see here the Terminal looking very worst, We have to make it beautiful
![Step 10](images/10-worst.png)<br/>

## Step 10:
Now go to [this](https://github.com/romkatv/powerlevel10k/blob/master/font.md) page and `copy` the font download link.
![Step 10](images/10-copy-link.png)

## Step 11:
![Step 11](images/11.png)<br/>
Now go to `fonts` directory by `cd` command

    cd /usr/share/fonts/

## Step 12:
![Step 12](images/12.png)<br/>
Pest this command into your terminal and Hit <kbd>Enter</kbd>

    sudo wget https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf

## Step 13:
![Step 13](images/13.png)<br/>
Now give this command and see your downloaded font name `MesloLGS NF Regular`

    ls

## Step 14:
![Step 14](images/14.png)<br/>
Now clear the terminal by this command

    clear

## Step 15:
![Step 15](images/15.png)<br/>
`Right` click on mouse and go to `Preferences`<br/>


### Go to `Appearance` tab. Make sure uncheck `Use system font`. Click on `font name`, in Mycase it's `Monospace Regular`<br/>
![step](images/16.png)


## Step 16:
Now search `MesloLGS` and click to `select` this font
![Step 17](images/17.png)<br/>
After selected font click `Close` to quite this Preferences

Now it's look like:
![look](images/18.png)<br/>

## Now switch to `root user`

    sudo su
![look](images/19.png)<br/>
## Run this command again
    bash -c "$(wget -qO- git.io/zsh.sh)"

This time previous all steps are same and password will not required.

## Final step:
After finish all process type this command

    sudo reboot

<h1 align='center'>Best of luck</h1>
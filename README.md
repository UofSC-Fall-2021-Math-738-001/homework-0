# Homework Null 

This homework is your chance to get up to speed on the tools 
used. The actual math should be very easy. 

I am assuming that you already have a TeX compiler installed on 
your prefered machine. If not, then take a look the 
[installation instructions for TeX Live](https://www.tug.org/texlive/). 

We are using GitHub Classroom for managining assignment distribution, 
submission, and feedback. To get started, you will first need a 
local installation of Git and a GitHub account. 

## Steps for getting setup with Git and GitHub

1. Register for account on GitHub (https://github.com/). 
We recommend using a username that incorporates your name 
(chase, marshall, skye).

2. Install Git on your favorite machine 
(https://github.com/git-guides/install-git) if it isn't already there. 

3. Configure Git. Open a terminal shell in your OS. And enter 
```bash
git config --global user.name 'Jane Doe'
git config --global user.email 'jane@example.com'
git config --global --list
```
replacing the name and email with what you used for registering your 
GitHub account. 

### SSH Keys for easier authentication (Optional)

5. [Generate a SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

6. [Add your key to your GitHub account](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

7. [Test your SSH connection](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

 
## Visual Studio Code

Next, you will want an editor that integrates well with GitHub. 
I've set up the assignments so that they can easily be opened in 
[Visual Studio Code](https://code.visualstudio.com/).

1. [Download and install VS Code](https://code.visualstudio.com/download)

2. You will probably want some tooling writing TeX. There are 
two extensions that I recommend: 
- [Latex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) is the most popular and 
fully-featured one 
- [TexLab](https://marketplace.visualstudio.com/items?itemName=efoerster.texlab) is a more modern approach that is still filling out 
a bit. 

3. [Install the GitHub Classroom extension](https://marketplace.visualstudio.com/items?itemName=GitHub.classroom) This extension 
simplifies both the process of submitting assignments via Git and 
allows for a pleasant remote collaborative experience. 

You can click on the `Open in Visual Studio Code` badge above to help with the installation process. 

Read through the documentation at (https://marketplace.visualstudio.com/items?itemName=GitHub.classroom). 


## Finishing the assignment 

1. Edit `hw.tex` to solve the mathematical problem. 

2. After finished, sync your changes back to GitHub, by 
clicking the `Sync Changes` button in the header bar of the 
`Assignment` view (the circular arrow button). 

3. I will respond with some feedback after syncing, through 
perhaps not immediately. To see the feedback, click on the GitHub icon 
on the left menu in VS Code. 


## Power users 

The GitHub Classroom extension in VS Code is a wrapper simplifying 
your interaction with Git. VS Code also provides a convenient 
environment for writing TeX (or in most languages) and a rich 
extension ecosystem. 

To customize your setup, you, minimally, only need 
- a TeX compiler,
- an editor for the TeX files,
- Git, and
- a GitHub account.

Feel free to trick out your local setup but be aware that I won't 
be able to assist with all personal setups. 
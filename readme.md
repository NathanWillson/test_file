Push code to github for the first time
How to Upload First Project on #GitHub
## Git-hub

go to **https://github.com**  sign-up, create a account

Use these commands in windows "cmd", mac-OS Terminal or linux-Treminal

## SSH Key Management

The below commands are used to manage SSH keys on your local development machine.

1. In treminal run command
    **cd ~/.ssh/**

2. check for existing SSH key
    **ls**

3. if no files exits then create or generate new  SSH key
    **ssh-keygen -t rsa -b 4096 -C "EMAIL ADDRESS"**

    ask for file name just press enter for default
    ask for passphrase **enter passphrase** for extra protection if key is stolen

    always keep key private do not share

4. copy key generated
    **ls**
    **cat id_rsa.pub**

5. get back to **https://github.com** 
    go to **settings**
    go to **SSH and GPG keys**
    click **New SSH key**
    *paste the key* and name **Title**





## git
1. in treminal run command
    **git config -l**
    if blank,then run

    **git config --global user.email "email@email.com"**
    **git config --global user.name "User-Name"**

    it will create a default email and name for this system

    *Note: This only needs to be done the first time you use Git on your machine*


2. Initialise a new Git repository

    **git init**


3. Commit changes to Git

    **git add .**
    **git commit -am "Commit change message"**

4. Set Git remote

    *Note: This only needs to be done once only*

    **git remote add origin <URL TO PROJECT>**

    changes
    **git remote add origin https://<username:tokenkey@>github.com/filename.git**
    
    git remote add origin https://NathanWillson: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@github.com/NathanWillson/testfile.git
5. changes
    NathanWillson
    
6. set Git Branch
    **git branch -M main**    


7. Push changes to GitHub
    **git push -u origin main**

8. to remove git remotre
    **git remote remove origin**
9. view git remote
    **git remote -v**
10. for git status
    **git status*

    this is how to push our first file
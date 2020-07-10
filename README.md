# git-is-fun-to-learn (Creating and Cloning)

This is a repository for people new to development and who want a safe space to practice in GitHub. There's no important or sensitive information in this repository - so you won't break anything by playing around - I promise! You will need to know some basic commands for the terminal though - so if you need a refresher, please visit https://github.com/jessufgit/terminal-cheat-sheet.

For this part of the series, you will complete two activities --
  1) Clone an existing repository to your desktop.
  2) Create a repository on your desktop that links to your Git Hub account.
  
 Enjoy!
 
 ------------------------------------------------------------------------------------------------------------------------------------------------

### Clone a repo directly to your desktop

  In this activity, you will clone a repository that already exists on Git Hub to your computer. 
  
  Using the terminal, create a folder on your desktop, and navigate into it. Then run...
  
      $ git clone https://github.com/jessufgit/git-is-fun-to-learn

  You have just cloned a git repository that I shared with the Git Hub community! Inside the folder you created on your desktop, you will see my project. 
  If you navigate into that folder, you will see this README. Great work!
  
 ------------------------------------------------------------------------------------------------------------------------------------------------
 
 ### Create your own repository from the command line
    
  In your terminal, create a folder and navigate into it. Then run the following (making sure to replace the starred section of the README with a line from your favorite movie)....
  
      $ echo "# **** favorite movie line here ****" >> README.md
      $ git init
      $ git status
        
   See that line in red? It's telling you that you have a file that is waiting to be committed to git hub - and that file is README. Now run....
   
      $ git add README.md
      $ git commit -m "first commit"
   
   You now have your README staged and ready to share with a repository on Git Hub. But in order to get that README into a repository on Git Hub, you will need to add a repository to your Git Hub account. This will create a connection between what you are working with locally and the place where you will keep these changes on Git Hub.
   
   Make sure you are logged into Git Hub. Click on Repositories and the green New button to create a new repository. Give your repository a name and click Create Repository. In the section that starts "…or push an existing repository from the command line" you will find your last two terminal commands.
   
   Now run those commands....
      Mine look like...
      
      $ git remote add origin https://github.com/jessufgit/practice.git
      $ git push -u origin master

If you look on Git Hub now, and refresh the page for your new repository, you should see the README has been added. Congratulations - you have just created a repository on Git Hub and are keeping a local copy of it on your computer that you can push and pull from.

### Checkout part 2 of this Git Hub practice series at jessufgit/git-is-fun-to-learn2 and keep learning! 

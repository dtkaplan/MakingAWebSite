# How to make a website

## A collaboratively constructed construction

### Create a Repo on Github

  1. ask for a new repository
  2. name it
  3. check to add a readme file
  4. you can probably ignore the license for this purpose
  5. click to build the repository
  6. Celebrate your success!
  
### Create index.md in the docs folder

  1. Click on the "Create a new file" (left of the bright green button)
  2. For the name of the file type doc/ and then index.md
  3. Type some text and commit it.
  
### Adjust your Settings

  1. Enable GitHub pages
  2. Choose "master branch /docs folder" method.
      * This only works if you created the file in the previous step, so do that first.
  3. Choose a theme if you like.
  4. After a brief delay, your website will be available.  This one is at [https://dtkaplan.github.io/MakingAWebSite/](https://dtkaplan.github.io/MakingAWebSite/)
  
### Now you can move to working in RStudio

  1. Grab the URL from the "Clone" button (bright green)
  2. In RStudio, create a new project, from version control, Git
    * paste in the git URL you copied from Github
    * choose a location for the repository
    * Click OK.
  3. You should now have all of your work from github on your machine.
  4. When you edit files, you need to communicate this to GitHub in the Git tab in RStudio
    * Click the buttons (typically next to a blue M or a yellow ?) for the files you have edited
    * Click commit (to take a snapshot)
    * Click push (to send the snapshot to GitHub)
  5. You can use Rmarkdown to create your HTML files.
    * Make sure you work inside docs/ and its sub-folders
    * Make sure you commit both the Rnw and HTML files (the web side needs the HTML, but R creates it for you, so you won't need to edit it.)
    
## Want to add a tutorial

Put a link to the tutorial [like this](https://dtkaplan.shinyapps.io/Statistics_formulas/).
  
  
  ![git commit messages](https://imgs.xkcd.com/comics/git_commit_2x.png)

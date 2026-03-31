[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zRhqrUys)
In VS Code, press Ctrl+Shift+V to preview this README.md file or Cmd+Shift+V on a Mac.

# CIDM6303-project-website 
The instructions for this assignment can be found at   
([https://docs.google.com/document/d/1t0HVdxquGlLDm93fHUsmnHKNRfpCyVy2lPanDvhqcwg/edit?usp=sharing](https://docs.google.com/document/d/1_8pdG7UyryCE1qQ9P-fgnLWMNEyqin12/edit?usp=sharing&ouid=101740201289965027466&rtpof=true&sd=true))  
index.html is ready for you to edit. Add additional files as needed. 

## How to view a webpage
To preview a webpage, right-click a file and choose Open in Live Server, assuming you have installed this recommended extension. 

## Looking for images to use
Public domain photos (https://www.publicdomainpictures.net/en/index.php)  
Generate AI clipart (https://www.emojis.com/)  
Flickr creative commons (https://www.flickr.com/creativecommons/)  

Remember these best practices: 
1. Put your image in the images folder.
2. Lowercase all file names; use hyphens or underscores if desired—NOT spaces in the file name. Different web servers process upper and lowercase files differently. 
3. Attribute the source and author if using someone else's creative content.

## Useful GIT Commands:  
Use the terminal or command line to issue git commands. 
  
**Typically, configure your settings only once per computer**, unless you need to update your name or email address in the future or switch computers. Git saves this information on your computer. *Substitute your name and email address*. This information will be used to log who made which changes to the code.
```bash
 git config --global user.name "Sample Student" 
 git config --global user.email sstudent@wtamu.edu
```
To ensure proper line endings:

On Windows, run:
```bash
git config --global core.autocrlf true
```
On Mac/Linux, run:
```bash
git config --global core.autocrlf input
```
For more on PC vs. Mac/Linux [line endings](https://docs.github.com/en/get-started/git-basics/configuring-git-to-handle-line-endings)

**To clone an assignment for the first time, follow these commands.** Run this command for each assignment. If you use multiple computers (e.g., work, home, school), run it once per computer per assignment. The URL to your assignment repository is found under the [Code] button and "Clone with HTTPS" on GitHub.com.
```bash
 git clone https://github.com/username/something  #use the URL to your specific assignment repository on github.com
 ```

**At the start of your coding session each day**, you should issue the following command to verify you have the latest changes from the online repository or to pull down any changes/comments made by the professor.     
```bash
 git pull  
 git status 
```
You should see the message "Your branch is up to date with 'origin/master'" and "nothing to commit."   
 
**At the end of each day (or after your class period) you should run these commands** to upload your changes to your online repository. The professor can view your changes.     
```bash
 git add -A
 git status    
 git commit -m "Type a message here in quotes that briefly describing your changes"
 git status    
 git push
 git status   
```
The first 'git status' should report that files have changed or been added and need to be committed. The second status should say "nothing to commit." The third status should report "Your branch is up to date with 'origin/master'" and "nothing to commit."  

After you are familiar with the Git workflow, you can skip the 'git status' commands, but they are useful for beginners to see what is happening at each step.

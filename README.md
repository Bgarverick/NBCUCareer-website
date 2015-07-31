# NBCU Website
## TODO
#### O&TS Webpage
@kcajmagic
- [ ] CSS
- [ ] HTML

##### Issues still on O&TS page
1.  [ ] New Text
2.  [ ] Campus 2 Career Logo 
3.  [x] Share button
4.  [ ] Pictures in dropdowns 
5.  [x] Make the bar clickable not just name on bar

These are some issues I (Ben) @Bgarverick think we need to resolve on the current O&TS Page

#### NexTech Webpage

- [ ] CSS
- [ ] HTML

#### C2C
- [ ] CSS
- [ ] HTML

## How to Run
For thouse who want to see how it looks. Download the zip file. And run the html file in question. For example if you want to see teh O&TS page run operations-and-technical-services.html

## How to view what is availble
In Terminal run the following commands
```
git clone https://github.com/Bgarverick/NBCUCareer-website.git
```
Wait to download file
To update your current folder with content on github run the command
```terminal
git pull
```

## How To use the gui with Firewall
1. Start by showing hidden files and folders, to do this visit: http://windows.microsoft.com/en-us/windows/show-hidden-files#show-hidden-files=windows-7
2. locate the .gitconfig under your username on your machine
3. Open the file with a text editor 
4. At the end of the file add the following lines
```
[http] 
	proxy = http://proxy.inbcu.com:80 
[https]
	proxy = https://proxy.inbcu.com:80
```
5. Save and close the text editor
6. Open the gui and navigate to clone and click NBCUCareer-website
7. Clone it to a file on your computer
8. Push it by clicking sync in the gui

## Git Commands

####Create your own Branch
*use your last name as your branch name*
```
git branch <lastname>
```

####Get Files From the master branch
```
git pull origin master
```

####Add Changed Files
```
git add --all
```

####Commit changed Files
```
git commmit -m "<message>"
```

####Push Changed files to server
```
git push origin <branchname>
```

####Merge branch with master
*Use when done with a feature*
*REMEMBER TO Push Commited files first to your branch*
```
git checkout master
git merge <branchname>
```
_If you have a merge conflit. I have not ran into it yet so there is not documentation._



								

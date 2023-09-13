# How to edit this site

This site is built using [docsify](https://docsify.js.org/#/). It is a static site generator that uses markdown files to generate a website. The markdown files are stored in the `docs` folder. The `index.html` file is the entry point for the site. It is a single page application that uses the `docs` folder as the source for the content.

> NOTE : Steps 1 and 2 are not mandatory if you don't want to test the site out locally, you can just make changes using notepad/VSC and push it to github. The site will be automatically updated.
### Step 1 - Install docsify
Install docsify globally using npm (node package manager)
```bash
npm i docsify-cli -g
```

### Step 2 - Run the server
Run the docsify server in the `docs` folder (Navigate to the parent of the `docs` folder and run the command)
```bash
docsify serve docs
```

### Step 3 - Edit the files
- All media files go in `_media` folder.
- Every group of pages goes in a folder.
- Every page is a markdown file withe the extension `.md`.
Edit the files in the `docs` folder. The changes will be reflected in the server.

### Step 3.5 - Add a route
If you are adding a completely new page , then go to the file name `_sidebar.md` and add your page to the sidebar. The sidebar is the navigation bar on the left side of the page. It is a markdown file that contains the links to all the pages. The format is as follows:
```markdown
- [**NAME YOU WANT TO DISPLAY**](/PATH/TO/FILE.md)
```

### Step 4 - Deploy

The site is hosted on github pages. To deploy the site, push the changes to the `main` branch. It will automatically be deployed to github pages.
You will need the git token to push to GitHUb, look up how to do that if you don't have one.
```bash
git add *
git commit -m "COMMIT MESSAGE"
git push
// These are the commands you need to push to github
```
> Always `git pull` before you push or edit anything to avoid merge conflicts


### Step 5 - Marvel at your creation
Tech literate or not, you have now added / edited a page on the QQC Library. Congratulations!
> For any queries, contact your nearest tech enthusiast and in the worst case, `swapnilnair747@gmail.com`


> Footnotes : 
>- Markdown can be edited using any text editor. However, it is recommended to use a markdown editor like [VS Code](https://code.visualstudio.com/) with the [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) extension.
>- If you **really can't write markdown**, and you don't want to learn it, you can use the [StackEdit](https://stackedit.io/app#) online editor. It is a WYSIWYG editor for markdown. I would not reccommend it if you want to add files to the site, but if you just want to edit the text,and links you can use it

### Step Noob
If you didn't understand a single word which was given above like another dumbass club head didnt, simply follow religiously what is given below
>- Install Git Bash(search git bash download and download from the git official website)
>- Install Microsoft Visual Studio Code(Yes this is what they would have told you to install in your first or second sem for your CS projects)
>- Open Git Bash
>- Type git clone < url >
(Here what is happening is you are cloning the github repository from Github to your computer thereby making a local copy of it)
>- When you do the previous step, it will tell you where the Github repository was cloned into. See properly the address where it is stored and go to File Explorer and see if you can access it via the path mentioned. Sometimes you have to go to C drive and access it and not directly from Documents shortcut(it was like that for me)
>-In Visual Studio install Markdown-All-in-One Extension(the link would have been given in a previous step or you can go to extensions in VS code and download from there)
>-Next open the library folder from wherever you have cloned the repository from. A new workspace should open. Once you do this you dont need to clone again and again. Directly you can open the library workspace and make yuor changes
>-Now to make changes, open the section where you want to change/edit stuff. 
>-To edit in the website, open git bash
>-Now see whether git bash is in the library directory. To see whether its there or not your command line should show something like ~/Documents/Library.
>-If it does not type cd <path of library>
>-After that follow steps in Step 4 above
>-In the commit messsage text you can add anything(basically add what youre editing thats all)
>-And yeahh you've saved yourself from the embarassment of not knowing how to edit a github website


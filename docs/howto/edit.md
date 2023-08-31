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




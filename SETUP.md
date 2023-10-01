# REACT APPLICATION ON GITHUB PAGES

## TOOLS USED
- [REACT](https://react.dev/)
- [VISUAL STUDIO CODE](https://code.visualstudio.com/)
- [GITHUB](https://github.com/)

## PURPOSE
- **WHO?** : REACT IS A VERY POPULAR FRONTEND JAVASCRIPT LIBRARY
- **WHAT?**: HOST STATIC WEBSITE FOR FREE
- **WHY?** : PORTFOLIO, LANDING PAGE, PROJECT SITE
- **WHERE?** : ON GITHUB


## SETUP
- CREATE NEW REPOSITORY
- CREATE REACT APP : `npx create-react-app mysite`
- CHANGE DIRECTORY : `cd mysite`
- USE GIT COMMANDS
```
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/xDevxnet/mysite.git
git push -u origin main
```
- INSTALL GITHUB PAGES DEPENDENCY PACKAGE : `npm install gh-pages --save-dev`
- ADDING DEPLOY SCRIPTS IN PACKAGE.JSON
```
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```
- ADD HOMEPAGE URL TO PACKAGE.JSON 
```
"homepage": "http://xdevxnet.github.io/mysite",
```
- PUSH CODE TO GITHUB
```
git add .
git commit -m "setup gh-pages"
git push
```
- START REACT APP : `npm run deploy`

# ALL DONE!
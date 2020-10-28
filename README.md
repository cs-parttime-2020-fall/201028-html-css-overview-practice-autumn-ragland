# 20-10-28 HTML CSS Overview Practice

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode

### Linking files
1. create an html file called `index.html` and use the `html:5` shortcut to generate the html, head, and body elements
2. create a css file called `style.css`
3. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
4. check that the files are linked by setting the `background-color` property of the body to any color other than white/gray and open thew HTML file using `ctrl o` in the browser

### Assignment
You will recreate the `wireframe` image created by following the steps in the content and styling sections below. The image, YouTube video, and google font in the completed HTML file do not have to match the wireframe image exactly. 

### Content
1. create a header element with an h1 with the text `20 10 28 Practice Assignment` and an h3 with the text `HTML CSS Overview - Halloween Edition`
1. create a button with the text `Check out these halloween movies` that links to [this](https://www.townandcountrymag.com/leisure/g12107335/best-classic-halloween-movies/) site 
1. create a div element with an iframe of a halloween music playlist on YouTube and a halloween image from [unsplash.com](https://unsplash.com/)

### Styling
1. set the background of the body to orange
1. embed a spooky google font of your choosing and set the heading 1 element to that font family 
1. set the button color to red with rounded edges and white text
1. use a pseudo class to set the button to a white background with red text on hover
1. give the iFrame and halloween image a thick black border and the height of both elements to 500px

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation Info on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/html.md)

[Google Fonts](https://fonts.google.com/)

# How to add new icons to iconfont

1. Go to [Icomoon App](https://icomoon.io/app/)  

2. Choose to manage projects on the far right side of the header
(or on [this link](https://icomoon.io/app/#/projects))

3. Choose **Import project** and upload this file **ontotext-icons-icomoon-project.json** from the repository

4. Load the project

5. Click the **Import Icons** button on the top left and import an SVG file

6. The new icon should be selected

7. Click on **Generate Icons** button at the bottom of the screen

8. Find the new icon(s) in the list and click on **Get code** to get the CSS (this needs to be included in your css file later)
```CSS
.icon-caret-down1:before {
    content: "\e957";
}
```

9. Click Download to get a zip file with the generated font files

10. Get the font files (icons.eot, icons.svg, icons.ttf, icons.woff) from the archive and replace them in the project

11. Copy the CSS declaration for the new icon(s) into your CSS file (from **p.8**) (There is a FONTS section at the beginning of bootstrap-graphdb-theme.css)

12. Add new changes back to this repository
  1. Download the project json file from [Icomoon project page](https://icomoon.io/app/#/projects)
  2. Add new SVG files the the SVG export folder

*Icomoon only keeps changes in local storage for free accounts, so they will be lost otherwise*

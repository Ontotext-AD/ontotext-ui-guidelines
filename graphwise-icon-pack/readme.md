# Graphwise Icons Font

This is a custom icon font for Graphwise, containing only approved icons and used only when no suitable standard alternatives exist.

The purpose of this font is to keep all custom icons in one place and aligned with Graphwise design decisions.

---

# How to add new icons to the icons font

1. Go to the [IcoMoon App](https://icomoon.io/app/).

2. Choose **Manage Projects** from the far right side of the header  
   (or use [this direct link](https://icomoon.io/app/#/projects)).

3. Select **Import Project** and upload the file  
   **`graphwise-icons-icomoon-project.json`** from the repository.

4. Load the project.

5. Click the **Import Icons** button in the top-left corner and import the new SVG file.

6. Ensure the new icon is selected.

7. Click the **Generate Icons** button at the bottom of the screen.

8. Find the new icon(s) in the list and click **Get Code** to obtain the CSS declaration  
   (this will need to be included later in your CSS file):

```css
   .icon-repo-fedx:before {
       content: "\e905";
    }
```

9.  Click Download to get the ZIP file containing the generated font files.

10. Extract the font files (icons.eot, icons.svg, icons.ttf, icons.woff) from the archive and replace the existing ones in the project.

11. Copy the CSS declarations for the new icon(s) (from step 8) into your CSS file.

12. Keep track of changes in this repository:

    - 1 Download the project json file from [Icomoon project page](https://icomoon.io/app/#/projects)
    - 2 Add new SVG files the the svg export folder.
    - 3 Update **icons-demo files** with the contents of the latest zip file from iconmoon

*Icomoon only keeps changes in local storage for free accounts, so they will be lost otherwise*

# How to replace an icon to the icons font
[Update icon procedure](../doc/update-icon.md)
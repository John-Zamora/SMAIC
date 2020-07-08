# SMAIC
> Repository for the development of SMAIC's website.  
_Last updated 07-08-2020_  

---

## Programming languages used:
1. HTML
2. CSS
3. JavaScript  

## Files included:
1. home
    - index.html
2. about
    - about-who.html
    - about-what.html
3. programs
    - programs-early.html
    - programs-elementary.html
    - programs-hs.html
    - programs-sped.html
    - programs-voc.html
4. admission
    - admission.html
5. contact
    - contact.html
6. styles
    - styles-mobile.css
    - styles-desktop.css
7. resources
    - logo.png  

---

## HTML
***Try to code for inclusion. Follow ARIA guidelines whenever possible.***  

### Head tag
**The head tag is made up of five main groups of elements**
1. General meta tags
    - Description is used to provide a description of the page
    - Viewport is used to define how the website is to scale on a device
    - Theme-color allows some devices to show a specified color on the surrounding user interface
2. Schema.org meta tags
    - Schema.org is a collaboration between the major search engine providers
    - Specifying the three tags will enhance what the user sees when the page is a result of their search
3. Facebook OG meta tags
    - The OG meta tags are there to improve user experience when the page link is shared on facebook
    - The users who see these links on Facebook will see a customized title, description, image, etc.
    - Omitting these tags will result in the link looking blank on Facebook
4. Icons
    - Having these icons are mainly for the branding and overall look of the site
    - It will allow the website to have an icon on multiple platforms
5. External files
    - The two files linked are the mobile and desktop stylesheets  

### Body tag
**The body tag is made up of four main groups of elements:**
1. Nav
    - Houses the five main links
    - Uses relative file paths
2. Main
    - Houses the main content of the page
    - Container elements use class naming, while the actual content uses id naming
    - This is to easily differentiate the grid container from the site content
3. Footer
    - Currently just contains the copyright information
4. Script
    - Houses the JavaScript code for the page  

---

## CSS
***The website utilizes grid to layout the elements on the site***  

### Values used
- vw
- vh
- fr
- rem  

### Mobile vs. Desktop
- Majority of the CSS code is written on the mobile stylesheet
- The desktop stylesheet uses media queries to change parts of the mobile styles
- Currently, the media queries will trigger when the device width is more than 650px
- The average device width falls under 600px, but that data was not as recent, thus a margin of 50px was applied
- The media query will also trigger if the desktop browser window is scaled horizontally to a size smaller than 650px
- This means that the mobile styles will take effect if the user shrinks his browser to certain width  

### Global styles
- Currently, the website contains styles applicable to all pages
- These include the font, the color variables, and the scroll-snapping
- Note that altering the font size of elements should be in ***% units***
- When applying colors to an element, define the variable instead of a hard-coded color value
- Defining a variable instead would allow the color of the elements to be easily changed later on, if necessary  

### CSS reset
- The style sheet contains a css reset to ensure no random margins or padding during coding  

### Naming convention
- Elements are generally uniquely named
- This means that even if they use class tags, no two elements currently have the same class name
- This was done because the website is still in its initial version, so the structure may still be altered
- In addition, the elements have unique names specifically so that some parts may be removed without the styles of others being affected
- The website can be minified or optimized later on, where proper class and id names may be assigned  

### General flow
- Styles may be applied to element's semantic tags, class tags, or id tags
- As stated prior, container elements are assigned ***class*** tags
- The specific content of those containers are assigned ***id*** tags
- Again, this can be changed later on when the site is to be minified  

- The main container elements are single columned and have a width of 100vw
- Note that there were some instances where the main container uses a value of ***fr*** due to weird spacing bugs; this will be revisited later on
- Rows generally have a value of ***auto*** because they should expand only as much space as they use
- This is to ensure that the sub-containers do not go beyond the width of the user's device
- The sub-containers follow a 12-column layout
- A 12-column layout is in use because it is the most flexible, wherein 12 is divisible by 6, 4, 3, and 2  
- Some sections needed to utilize ***grid-area*** because there would be times when the order of the HTML content had to be changed  

---

## JavaScript
***There is currently no JavaScript code on the website***

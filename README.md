# SMAIC
> Repository for the development of SMAIC's website.  
_Last updated 06-23-2020_  

---

## HTML
**The following lines will discuss the HTML aspect of the SMAIC website.** 

The contents include:  
1.  The home page
2.  The admissions page
3.  The student life page
4.  The about page \(our vision\)
5.  The contact page  

Under those five sub-headings, the following topics will be discussed:
- Structure
- Classes and IDs
- Other things to note  


### Home
#### Structure
#### Classes and IDs
#### Others  

### Admissions
#### Structure
#### Classes and IDs
#### Others  

### Student Life
#### Structure
#### Classes and IDs
#### Others  

### Our Vision
#### Structure
#### Classes and IDs
#### Others  

### Contact
#### Structure
#### Classes and IDs
#### Others

---

## CSS
**The following lines will discuss the CSS aspect of the SMAIC website.**

### Mobile
- The website was designed for mobile
- Media queries were used for the desktop styles


### Desktop
- A separate CSS file is used for the desktop styles
- The desktop styles are activated through the use of media queries
- The minimum device width to trigger the use of the desktop style is currently 600px
- Note that the resizing the browser width to that certain point will also trigger the mobile style


### General Points
- Units used:
    - fr
    - %
    - vw / vh
    - rem
- The website generally utilizes a 12-column layout because 12 is easily divisible by 1, 2, 3, 4, and 6, thus providing more flexibility
- Generally, current naming convention makes every item virtually unique, but I have the tendency to have container elements use the *class* tag, while child elements of those containers use the *id* tag


### Structure
- Each page has a main section
- The main section houses virtually all of the content
- Only the main navigation bar and the footer are not under the *main* section
- The main section of each page will always establish a 100vw column -- this is to ensure that the main content only takes up as much space as the screen has, thus no horizontal scroll bars
- The child elements of the main container element would use fractional units following the 12-column layout
- The child elements of the containers using fractional units, which should be the actual content of the website, would only use percentages to define how much space they would take up
- To recap:
    - Each page has a main container element
    - The main container element would have children elements
    - Those children elements serve as containers for the actual content of the website, such as the images, paragraphs, headers, etc.
    - The main container element will always have a single 100vw column to ensure that the content will only consume as much space as the device width can offer
    - The child elements use fractional units to divide the space they have, and note that they follow a 12-column layout
    - It is recommended that the actual content uses percentages to define how much space of the container they will use up
    - This is because it is expected that the container element already defines where the content will be and how it is oriented in the page
---

## JavaScript
**The following lines will discuss the JavaScript aspect of the SMAIC website.**

# The Tea Cozy
*This project has been completed as part of a full- stack development course at Codecademy.*

## Introduction
The aim of this project was to create a site for a client that needed a responsive site that worked across all device types and screen sizes.

## Technolgies
- HTML
- CSS
- Git
- GitHub
- Chrome Devloper Tools

## Live Site
The site is being hsoted on GitHub Pages here:
https://laith8910.github.io/Tea-Cozy-Website/

## Techniques Used
In order to make the site reactive I primarily used a pair of techniques designed around the visual breakpoints of the site, utilising CSS media queries and flexboxes.

#### Examples of use
Here is an example of my use of Flexboxes in my project:
``` css
#flex{
    display: flex;
    flex-flow: row;
    justify-content: space-around;
    flex-wrap: wrap;
    align-items: center;
}
```
Here is an example of my use of CSS media queries in my project:
``` css
@media screen and (max-width: 500px) {
        #logo{
            position: relative;
            left: 0px;
        }
        header div {
            background-color: black;
            text-align: center;
        }
        header div p {
            display: inline-block;
            position: relative;
            text-align: center;
        }
    }
```

## Project Status
**This project is complete!**
I may return to this projet at a later date to add more functionality.



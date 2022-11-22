# HTML CSS Git Challenge: Code Refactor

## Description

This project was created for the first challenge of a Front-End Web Developer Bootcamp. We were provided with starter code and assets for a website for Heriseon, a marketing agency. Heriseon wanted a codebase that followed accessibility standards so that their site was optimised for search engines, the current starter code did not reflect this.

Throughout this project I worked through the following in order to achieve that goal:

1. Update the HTML file to use semantic HTML elements and follow accessibility best practices
2. Consolidate and organise the elements in the CSS file
3. Ensure both files used logical structuring and had appropriate comments
4. Ensure the live site replicated the mockup after changes had been made and all functionality remained

Working through this project I realised a lot of the same functionality can be achieved using more condensed HTML and CSS, while also providing a more accessibile website.

## Table of Contents

- [Description](#description)
- [Installation/Usage](#installation/usage)
- [Challenges](#challenges)
- [Resources](#resources)
- [Credits](#credits)
- [License](#license)

## Installation/Usage

### Screenshots

md
    ![Heriseon Social Solution Services website](assets/images/screenshot.png)

### Users

To visit the website, [please click this link.](https://LINKGOESHERE.com)

You will be directed to the webpage where you can navigate through the content using the header links. You will also be able to inspect the code using the developer inspector and review the HTML, CSS and accessibility features.

### Developers

1. Navigate to the main page of the repository
2. Click the green 'Code' button and copy the SSH or HTTPS key
3. In terminal (Mac) or Git Bash (Windows) clone into the directory you want the repo in using the 'git clone' command followed 
4. Open the directory in your code editor
5. Inspect the index.html file and css file to view all accessibility features and comments

## Challenges

While ensuring that the html was semantic I decided to change the 'hero' div to a figure tag. By doing this it meant I needed to change the background-cover and background-position selectors in the CSS file to be object-cover and object-position instead. Doing a little research I found that those selectors were unlikely to be supported in Internet Explorer and so I decided to remove these elements and return to using the original div.

## Resources

- [W3 Schools - HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Coding BootCamp GitHub Repo - Professional README Guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)
- [Markdown Guide - Basic Markdown Syntax](https://www.markdownguide.org/basic-syntax/)
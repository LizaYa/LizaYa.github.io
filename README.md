# Host Resume on Github Pages

This is a tutorial on how to easily host a resume using Jeykll, Markdown, Markdown editor, and Github pages.

The following instructions will explain how to locally test your resume using Jykll and how to host it on Github pages. 

## Prerequisites

* Prepared resume in Markdown format
* Installed Jeykll on your machine
* Markdown editor (such as Atom, Typora, Visual Code etc.)

## Instructions

* Name your repository ``github_username``.github.io
* Clone your repository and open the project in your text editor
* run the following commend inside the project directory: ``jekyll new yourProjectName``           
* move all the generated files to your project folder and delete the empty folder that is left. 
* run ``bundle add webrick``. You should end up with the following files:

    ![image](https://user-images.githubusercontent.com/56234653/159091902-780d86dd-46c1-4402-8904-2e321bebd908.png)

### Test your site locally

    bundle exec jekyll serve
    
## Deployment
* Commit your code 
* Your resume site should not be hosted on `github_username`.github.io

## Example:
![My Resume](ezgif.com-gif-maker.gif)

 ### More Resources:
 * [What is Markdown?](https://www.markdownguide.org/getting-started/)
 * [Markdown Tutorial](https://www.markdowntutorial.com/)
 * [Jekyll Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
 * [Markdown Editors](https://www.shopify.ca/partners/blog/10-of-the-best-markdown-editors)
 * [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)



 




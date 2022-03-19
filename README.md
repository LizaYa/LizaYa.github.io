# Host Resume on Github Pages 

This is a tutorial on how to easily host a resume using Jeykll, Markdown, Markdown editor, and Github pages.

## Getting Started

The following instructions will explain how to locally test your resume using Jykll and how to host it on Github pages. 

## Prerequisites

* Prepared resume in Markdown format
* Ruby version 2.1 or higher
* Markdown editor (such as Atom, Typora, Visual Code etc.)

## Instructions

1) Jekyll is a popular static page generator and as reccomended by Andrew Etter, we will be using Jekyll.
    #### Install Jekyll:
    In the terminal run `gem install jekyll bundler`
3) In this tutorial, we are using Github pages to host our resume. As was suggested by Andrew Etter, Github pages has not server dependencies and no database, so working with this is very easy. To use Github pages, first open a new repository and name it `yourGithubUsername.github.io`
4) Clone your repository and open the project in your text editor (I use VS code). We are using a Markdown editor as it is much easier and convenient.
5) Run the following commend inside the project directory: ``jekyll new yourProjectName``. This will create a Jekyll folder inside your project folder with all the required files.            
6) Move all the generated files to your project folder and delete the empty folder that is left. 
7) run ``bundle add webrick``. You should end up with the following files:

    ![image](https://user-images.githubusercontent.com/56234653/159091902-780d86dd-46c1-4402-8904-2e321bebd908.png)
8) You can modify the file `index.markdown` and write your resume there.

### Test your site locally
Testing locally your site before publishing it to your respository is very important. It allows you to view the changes and see what is the expected result.

    bundle exec jekyll serve
    
## Deployment
* Commit your code to your main branch 
* Your resume site should now be hosted on `https://yourGithubUsername.github.io/`

## Example:
![](ezgif.com-gif-maker.gif) 

[Click here for example](https://lizaya.github.io/) 

 ## More Resources:
 * [What is Markdown?](https://www.markdownguide.org/getting-started/)
 * [Markdown Tutorial](https://www.markdowntutorial.com/)
 * [Jekyll Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
 * [Markdown Editors](https://www.shopify.ca/partners/blog/10-of-the-best-markdown-editors)
 * [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors and Acknowledgments:
* Liza Yashin
* Template Authors - Github profiles: 
    - Billie Thompson
    - CaduGoncalves96

## FAQs
#### Question: 
Why is it a good idea to have a static page for your resume?
#### Answer: 
They are fast, simple, and reliable. You do not need any dependencies, databases, servers etc. It is much easier and convenient to update a static page and updating a a PDF resume and saving many copies of it on your machine.
#### Question: 
How can I remove the header and the footer?
#### Answer: 
You can open a folder `_includes` in your directory and add these files: footer.html and header.html. This will overwrite the header and the footer that Jekyll uses by default. 



 




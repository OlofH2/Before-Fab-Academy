I had a lot to learn and many steps to go through when creating this website. Even though [Svavar Konráðsson](https://fabacademy.org/2023/labs/isafjordur/students/svavar-konradsson/index.html) and [Þórarinn Bjartur Breiðfjörð](https://fabacademy.org/archives/2015/eu/students/gunnarsson.thorarinn_b.b/index.html) guided me through the whole process, it was a lot to learn. I ran into quite a few problems but in the end all worked out. First Svavar explained the basics.


**Prior knowledge**

A few years back I created a simple website using a template from [Wix](https://www.wix.com/). Then, a few months ago, I participated in adding information to a website made by Þórarinn Bjartur Breiðfjörð and [Svavar Konráðsson](https://fabacademy.org/2023/labs/isafjordur/students/svavar-konradsson/index.html). I did this by using GitHub web editor, so I had gotten to know editing Markdown a little bit. This helped me a lot.


**Understanding HTML+Javascript**

The first assignment was to copy a code from [here](https://www.w3schools.com/html/default.asp) and paste it into a NotePad. By saving the NotePad file as a HTML file it opens up as a webpage when doubleclicked on. This helped me to understand how HTML and Javascript work.


**Learning about CSS**

The next step was to learn about CSS, or Cascade Style Sheet, and how we can use CSS to control the way our HTML code appears, f.ex. the colour of elements, where text is situated and which fonts to use. On this page [here](https://www.w3schools.com/css/css_intro.asp) we could find explanations on CSS.


**Learning about Basic syntax/Markdown**

By reading about what to do and what not to do on [here](https://www.markdownguide.org/basic-syntax/) it helps when writing a Markdown. I took another look at this page after some coding and realized that I was not doing everything the right way. I should have put a blank line before writing a heading, instead of writing the heading at the top of the terminal. I also should have pressed the space button between the hashtag symbol and the text in the heading, instead of not leaving space inbetween.


**Cloning a repository**

In VS Code I cloned the repository from my GitHub account. Then I clicked on the three points in the top bar, chose *Terminal* and then to *Open a new terminal*. 


**Material for docs**

To set up Material for docs I installed a Python package by copying and pasting this code:<pip install mkdocs-material> from this [website](https://squidfunk.github.io/mkdocs-material/getting-started//) into the terminal.  ![PIP install](img/PIP_install_200x28px.jpg)

![Theme_Material](img/Theme_in_mkdocs_before_new_theme_200x113.jpg)

I saw that [Svavar Konráðsson](https://fabacademy.org/2023/labs/isafjordur/students/svavar-konradsson/index.html) added admonition to be able to add notes and more to his website. I decided to do the same and add admonition to my mkdoks.yml file from [here](https://squidfunk.github.io/mkdocs-material/reference/admonitions/). 


I also copied codes from the same site [here](https://squidfunk.github.io/mkdocs-material/reference/admonitions/) and adjusted the text to fit here on my page. The look and usage of admonitions can vary and you can learn more about it here:

!!!Info
  
    Have fun changing admonitions by reading about them [here](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)


**Collapsable block**

??? note "Toggle the arrow here on the right side"

    I think it´s absolutely brilliant to be able to make a collapsable block, like this one, with a small toggle to the right.


**Inline block**

!!! info inline end "Inline blocks"

    It is important to place content after the code for inline blocks. The photo here on the left side is a screenshot from [here](https://squidfunk.github.io/mkdocs-material/reference/admonitions/), and so is the code that was used to make this Inline block. 

![Inline_code](img/Inline_code_example_400x150.jpg)

!!! note

    The photo is 400 pixels wide, 500 pixels was to wide so that the inline box did not fit beside the photo.



**Autosave in VS Code**

It is possible to turn on Autosave in VS Code and I find that helpful because when I am documenting my changes appear almost instantly on my website and I can check out regurlarly how things look.


**Compressing photos and videos**

In the beginning of my documentation I used the Snipping Tool 

![Snipping tool](img/Snipping_tool_b.jpg)

Since the size of all images was around 15-50kb I thought that they would be conveniently small for my website, and I decided to load them all up at the same time. When I checked out the website I saw that they were too big. 


**Loads of mistakes**

One of the mistakes I made when creating this site was to make two yaml files in my Actions folder. [Svavar Konráðsson](https://fabacademy.org/2023/labs/isafjordur/students/svavar-konradsson/index.html) pointed this out to me and I deleted one blank yaml file.

On Svavar´s site I saw that it was recommended to add a line to settings.json. I wrote the code myself after the code on his site, but something went wrong. After copying the code and pasting it in the right place it worked.

I knew that the number of hashtags in front of a sentence or a word controlled which type of heading was used and I thougt that if I used one hashtag in front of the headline I should use two hashtags in front of text that I wanted to be bigger than normal text. What I did not know was that the hashtags I was using also made the text appear in the Table of content. [Svavar Konráðsson](https://fabacademy.org/2023/labs/isafjordur/students/svavar-konradsson/index.html) saw this and he let me know so that I could fix this.

There are a few more things I learned from Svavar´s website. [Svavar´s website](https://fabacademy.org/2023/labs/isafjordur/students/svavar-konradsson/index.html). I noticed that when I clicked on links on his page to see the origin of codes he used, the links led me to exactly the right place on the sites he had linked to. I did´nt have to search the pages to find the origin. Svavar used this code so that other´s, who would link something to his page would end up on the right spot on his page. I decided to copy the code from his page and do the same.

  features:
      - navigation.tracking

I also copied this code from his page:

  features:
        - navigation.tabs
        - navigation.tabs.sticky
        
It makes the navigation at the top of the page follow when scrolling down a page.


*Ath að skoða markdown codeblocks


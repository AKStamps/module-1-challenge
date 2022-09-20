# **Module 1 Challenge for UNC Chapel hill Coding Boot Camp**

## **Project Description**

The goal of this project is to refactor existing code within a website for Horiseon Social Solution Services to meet accessibility standards and optimize site for search engines, this goal will be met with the following criteria.

<ul>
  <li>
  Use semantic HTML elements and remove any non semantic elements from code
  </li>
  <li>
  Add a descriptive title for the webstite
  </li>
  <li>
  Add proper ALT tages for all images
  </li>
  <li>
  Add proper indentation within HTML to clean up code
  </li>
</ul>

## <strong>Project Purpose</strong>
<p>
  The purpose and motivation for this project is to better understand and develop skills in the use and application of semantic HTML elements and website accessibility standards.
  In the time working on this project I have gained knowledge in the uses of semantic HTMl and image ALT tags for their applications with programs like screen readers for the visually impaired. I have also come to a better understanding of how semantic structuring of a website allows not only a better organized code but the ability for such programs to properly browse a site.  I have also learned alot about the uses and application of a README file in the professional workplace.
  </p>

### <strong>Screenshots</strong>
  
#### *The screenshots below showcase the original code for the website before alterations are made to include semantic elements.*

#### <strong>HTML</strong>

<figure>
  <img src="Develop/assets/readmeimages/Original Index Code 1.png" alt="Original Index code screenshot 1">
</figure>
<figure>
  <img src="Develop/assets/readmeimages/Original Index Code 2.png" alt="Original Index code screenshot 2">
</figure>
<figure>
  <img src="Develop/assets/readmeimages/Original Index Code 3.png" alt="Original Index code screenshot 3">
</figure>

##### CSS

<figure>
  <img src="Develop/assets/readmeimages/Original CSS Code 1.png" alt="Original CSS Code 1">
</figure>
<figure>
  <img src="Develop/assets/readmeimages/Original CSS Code 2.png" alt="Original CSS Code 2">
</figure>
<figure>
  <img src="Develop/assets/readmeimages/Original CSS Code 3.png" alt="Original CSS Code 3">
</figure>
<figure>
  <img src="Develop/assets/readmeimages/Original CSS Code 4.png" alt="Original CSS Code 4">
</figure>
<figure>
  <img src="Develop/assets/readmeimages/Original CSS Code 5.png" alt="Original CSS Code 5">
</figure>
<figure>
  <img src="Develop/assets/readmeimages/Original CSS Code 6.png" alt="Original CSS Code 6">
</figure>

#### Conclusions

<section>
  <p>
      As you can see from the screenshots the HTML file uses very few semantic selectors which would not allow it to pass accessibility standards.
    The website also does not have a descriptive name in the header and has disorganized class and ID selectors which become more apparent in the CSS file.
    The images in the HTML file also do not have any ALT tages which will not allow them to be read by a screen reader.
  </p>
  <p>
     The CSS file, although fully functional, is very disorganized and difficult to navigate due to a classes not being in sequential order with the webpage
    and several confusing class names.  The following screenshots demonstrate the refactored code.
  </p>
</section>

### Refactored Code Screenshots

#### HTML

<figure>
  <figcaption><strong>This screenshot shows the refactored HTML code within the head and header sections of the webpage.  Within the head the meta tag "viewport" has been added to adjust the page to fit different device screens and a descriptive title has been added for the webpage.  Within the header semantic elements have been added to accessibility as well as a note infoming anyone viewing the code that it is the header and navigation links section of code.</strong></figcaption>
  <img src="Develop/assets/readmeimages/Refactored HTML 1.png" alt="Refactored HTML screenshot 1" height="200px" width="200px">
</figure>
<figure>
  <figcaption><strong>This screenshot shows the refactored HTML code within the hero image section and Services section of the webpage.  The hero image section remains unaltered. Within the Services section semantic elements have been added, ALT tages have been added to photos to enable screen readers and the three figure class tags have been changed to ID tags within a single class tag labeled "services" for ease of use. Comments have also been added identifying the hero image section and services section for anyone viewing the code.</strong></figcaption>
  <img src="Develop/assets/readmeimages/Refactored HTML 2.png" alt="Refactored HTML screenshot 2" height="200px" width="200px">
</figure>
<figure>
  <figcaption><strong>This screenshot shwos the refactored code HTML within the Benefits section and footer of the website.  The benefits section has been refactored in an identical way to the Services section with semantic elements, the three figure Class tags changed to ID tags within a single class called "Benefits" and the images are given ALT tags for use with a screen reader.  A comment has been added to depict the section to anyone viewing the code.  The footer section remains largly unaltered with the acception of semantic elements added and a note depicting the footer text.</strong></figcaption>
  <img src="Develop/assets/readmeimages/Refactored HTML 3.png" alt="Refactored HTML screenshot 3" height="200px" width="200px">
</figure>

#### CSS

**The following screenshots show the refactored CSS code.  You can see that the sections have been moved into sequential order with the design of the web page beginning with universal elements selectors and going onward from that point.  Individual descriptive comments have been added to each section to allow ease of use for any other person viewing the code.**

<img src="Develop/assets/readmeimages/Refactored CSS 1.png" alt="refactored CSS screenshot 1">

<img src="Develop/assets/readmeimages/Refactored CSS 2.png" alt="refactored CSS screenshot 2">

<img src="Develop/assets/readmeimages/Refactored CSS 3.png" alt="refactored CSS screenshot 3">

<img src="Develop/assets/readmeimages/Refactored CSS 4.png" alt="refactored CSS screenshot 4">

<img src="Develop/assets/readmeimages/Refactored CSS 5.png" alt="refactored CSS screenshot 5">

<img src="Develop/assets/readmeimages/Refactored CSS 6.png" alt="refactored CSS screenshot 6">

<img src="Develop/assets/readmeimages/Refactored CSS 7.png" alt="refactored CSS screenshot 7">

<img src="Develop/assets/readmeimages/Refactored CSS 8.png" alt="refactored CSS screenshot 8">

<img src="Develop/assets/readmeimages/Refactored CSS 9.png" alt="refactored CSS screenshot 9">

## Project Conclusions

**After completeing this project to the best of my ability the conclusion I have come to is in two parts**

The first conclusion is that semantic HTML, in normal practice, is an absolute necessity.  Not only for the purposes of search engine optimization and accessibility but for the purpose of organization.  I can only imagine the amount of time that would be required to restructre a web page of much larger propertion if it had been written in the style of the projects unsolved code.  This goes hand in hand with effective and descriptive names of class and ID tags.  Semantic HTML and proper tags combined can save a tremendous amount of time for someone needing to alter the code and also provide the proper accessibility standard while doing so.

The second conclusion is that when it comes to a new project it is incredibly important to use semantic structure, proper spacing and comments from your first keystroke.  This entire challenge would obviously not have existed if it had been done this way and with the proper structure and a request to perhaps fix a link one could have beem done with this project in less than half an hour.  I will from here on out be certain to use this structure in any code that I created or alter.

### **Links** 

 

[Deployed Github Page](https://akstamps.github.io/module-1-challenge/)

[Github Repository](https://github.com/AKStamps/module-1-challenge.git)



  
  


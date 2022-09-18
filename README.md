# Module 1 Challenge for UNC Chapel hill Coding Boot Camp

## Project Description
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

## Project Purpose
<p>
  The purpose and motivation for this project is to better understand and develop skills in the use and application of semantic HTML elements and website accessibility standards.
  In the time working on this project I have gained knowledge in the uses of semantic HTMl and image ALT tags for their applications with programs like screen readers for the visually impaired. I have also come to a better understanding of how semantic structuring of a website allows not only a better organized code but the ability for such programs to properly browse a site.  I have also learned alot about the uses and application of a README file in the professional workplace.
  </p>

### Screenshots
  
#### The screenshots below showcase the original code for the website before alterations are made to include semantic elements.

##### HTML

<figure>
  <figcaption>Original Index.HTML code screenshot 1</figcaption>
  <img src="Develop/assets/readmeimages/Original Index Code 1.png" alt="Original Index code screenshot 1" >
</figure>
<figure>
  <figcaption>Original Index.HTML code screenshot 2</figcaption>
  <img src="Develop/assets/readmeimages/Original Index Code 2.png" alt="Original Index code screenshot 2">
</figure>
<figure>
  <figcaption>Original Index.HTML code screenshot 3</figcaption>
  <img src="Develop/assets/readmeimages/Original Index Code 3.png" alt="Original Index code screenshot 3">
</figure>

##### CSS

<figure>
  <figcaption>Original style.CSS code screenshot 1</figcaption>
  <img src="Develop/assets/readmeimages/Original CSS Code 1.png" alt="Original CSS Code 1">
</figure>
<figure>
  <figcaption>Orignial style.CSS code screenshot 2</figcaption>
  <img src="Develop/assets/readmeimages/Original CSS Code 2.png" alt="Original CSS Code 2">
</figure>
<figure>
  <figcaption>Original style.CSS code screenshot 3</figcaption>
  <img src="Develop/assets/readmeimages/Original CSS Code 3.png" alt="Original CSS Code 3">
</figure>
<figure>
  <figcaption>Original style.CSS code screenshot 4</figcaption>
  <img src="Develop/assets/readmeimages/Original CSS Code 4.png" alt="Original CSS Code 4">
</figure>
<figure>
  <figcaption>Orignial style.CSS code screenshot 5</figcaption>
  <img src="Develop/assets/readmeimages/Original CSS Code 5.png" alt="Original CSS Code 5">
</figure>
<figure>
  <figcaption>Original style.CSS code screenshot 6</figcaption>
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
  <figcaption>This screenshot shows the refactored HTML code within the head and header sections of the webpage.  Within the head the meta tag "viewport" has been added to adjust the page to fit different device screens and a descriptive title has been added for the webpage.  Within the header semantic elements have been added to accessibility as well as a note infoming anyone viewing the code that it is the header and navigation links section of code.</figcaption>
  <img src="Develop/assets/readmeimages/Refactored HTML 1.png" alt="Refactored HTML screenshot 1">
</figure>
<figure>
  <figcaption>This screenshot shows the refactored HTML code within the hero image section and Services section of the webpage.  The hero image section remains unaltered. Within the Services section semantic elements have been added, ALT tages have been added to photos to enable screen readers and the three figure class tags have been changed to ID tags within a single class tag labeled "services" for ease of use. Comments have also been added identifying the hero image section and services section for anyone viewing the code.</figcaption>
  <img src="Develop/assets/readmeimages/Refactored HTML 2.png" alt="Refactored HTML screenshot 2">
</figure>
<figure>
  <figcaption>This screenshot shwos the refactored code HTML within the Benefits section and footer of the website.  The benefits section has been refactored in an identical way to the Services section with semantic elements, the three figure Class tags changed to ID tags within a single class called "Benefits" and the images are given ALT tags for use with a screen reader.  A comment has been added to depict the section to anyone viewing the code.  The footer section remains largly unaltered with the acception of semantic elements added and a note depicting the footer text.</figcaption>
  <img src="Develop/assets/readmeimages/Refactored HTML 3.png" alt="Refactored HTML screenshot 3">
</figure>

#### CSS

The following screenshots show the refactored CSS code.  You can see that the sections have been moved into sequential order with the design of the web page beginning with universal elements selectors and going onward from that point.  Individual descriptive comments have been added to each section to allow ease of use for any other person viewing the code.



  
  


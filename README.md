# Unit 01 Homework: Marketing Company Landing Page

For this project, I'm working as a front end developer to solve on-the-job ticket request. The main requirement is to **Refactor** the existing code to make it more accessible. Accessibility can include complex requirements, but my tech lead has given a small list of specific criteria for this project. These criteria are documented in the Acceptance Criteria section.

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
   <br/>

## 💡 My Solution

After going through the requirement, I have listed down following key points to consider: 
1. Improve the the accessibility, styling and positioning of the logical structure:<br/>
   I've re-edited the code code by using the semantic HTML elements. I've fixed the broken link "Search Engine Optimization" by replacing the CLASS selection with ID  selector. As per original code, instead of using 3 different classes for simillar function, I've used the single class to maintain logical structure. For example -   "content-data" and "benifit-data". This has improved the CSS styling file structure. I've restructured the CSS file with appropraite comments. 

   > **Favicon**: I've created the favicon for this website using Photoshop and added it using the "link rel - icon" code in the head tag.
   
   <br/>

2. Modify Icon and image elements with accessibility alt attributes:<br/>
   There was no alt tags for icons and images in the original code. I've now updated the code with concise and focusd keywords to all the images. For the hero banner background image is reffered in the style.css file. I've added the descriptive keyphrase using the **title** tag as shown in the image below for this.

   ![Hero banner background image alt tag description.](./assets/readme-assets/hero-image-alt-tag.jpg)

   > **Image File Size**: None of the images were optimized for web. The collective file size was 47.7 mb. I've reduced the file size to 6.83 mb without loosing the quality of the images. This has drastically improved the page loading size.
      
   <br/>

3. Make all the heading attributes in sequential order:<br/>
   Skipping heading levels should be avoided from an accessibility point of view. People using screen readers often rely on navigating by heading so if the structure isn’t hierarchical they may not understand the relationship. For example, in the original code, as highlighted below H2 was followed by H3.

   ![Incorrect sequencing of heading tags.](./assets/readme-assets/heading-incorrect-formatting.jpg)

   I've corrected this by replacing the heading tag to H4 as shown in the image below:

   ![Correct sequencing of heading tags.](./assets/readme-assets/heading-correct-formatting.jpg)
   
   <br/>

4. Add a concise title:<br/>
   In the original code, title tag was not properly mentioned. I have now optimized the title tag with descriptive message using the correct keywords to improve ranking position on search engines.

   <br/>

## 🔗 Project Link

   https://ajaykulkarni01.github.io/Marketing-company-landing-page/

   <br/>





---



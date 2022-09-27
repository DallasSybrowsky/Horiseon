# Horiseon
Homework 1: Given the User Story and Acceptance Criteria below I refactored the original code. 

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

1. GIVEN a webpage meets accessibility standards
    * WHEN I view the source code
    * THEN I find semantic HTML elements

2. WHEN I view the structure of the HTML elements
    * THEN I find that the elements follow a logical structure independent of styling and positioning

3. WHEN I view the icon and image elements
    * THEN I find accessible alt attributes

4. WHEN I view the heading attributes
    * THEN they fall in sequential order

5. WHEN I view the title element
    * THEN I find a concise, descriptive title

## Homework
Background:  I updated the HTML to ensure it follows semantic guidelines by generalizing classes in the HTML. I also cleaned up the CSS file by eliminating duplicate lines of code and ensuring the style and content of the page remained as intended. 
Note: In order to make the grading and feedback process easier I added comments where I made changes, as well as in certain areas to increase clarity of the code in both HTML and CSS. 

Below are details on the methods I used to accomplish each of the items in the Acceptance Criteria:

1. I updated the numerous div elements throughout the code, and updated them to follow semantic HTML guidelines. Examples are changing div elements to more appropriate elements such as header, main, aside, section, figure, footer, etc.

2. When updating the numerous div elements as mentioned above I updated the elements so that each one better described the purpose of the code on the page. For instance I updated one div element and changed it to an aside element. In another instance I changed a div to main as the code within that section was the main content of the page. 

3. I ensured that the accessibility of the page was up to standard by updating the code within the img elements to include an alternative text for use with screen readers, as well as if the images or icons links are broken.

4. I updated the heading attirbutes in CSS to ensure they are in the correct order as shown in index.html.

5. The title element was changed to reflect the name of the company to provide a concise, descriptive title.

## Visuals
Below is a screenshot of the refactored webiste: 
<img width="400" alt="Screen Shot of Horiseon Website" src=".assets\images\DSybrowsky Horiseon Page.png">


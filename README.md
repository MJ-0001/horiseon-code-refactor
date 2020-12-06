# horiseon-code-refactor  
  
### High-level non-functional requirement from client:  
The code base shall meet webpage accessibility standards as per guidelines cited in https://www.w3.org/WAI/standards-guidelines/  
  
### User Story:  
* AS A marketing agency  
* I WANT a codebase that follows accessibility standards  
* SO THAT our own site is optimized for search engines  
  
### Acceptance Criteria:  
* GIVEN a webpage meets accessibility standards  
* WHEN I view the source code  
* THEN I find semantic HTML elements  
* WHEN I view the structure of the HTML elements  
* THEN I find that the elements follow a logical structure independent of styling and positioning  
* WHEN I view the image elements  
* THEN I find accessible alt attributes  
* WHEN I view the heading attributes  
* THEN they fall in sequential order  
* WHEN I view the title element  
* THEN I find a concise, descriptive title  

### Brief Summary of Changes:  
#### HTML  
* Introduced semantic elements - header, nav, main, section and aside tags to  
work with screen readers.
* Added indentation to code blocks to improve readability and maintainability.
* Added spacing between major code blocks to improve readability.
* Title added to webpage along with a favicon.
* Reduced and condensed the number of classes to simplify the code.
* Added comments to assist other developers with maintaining the code.
* Updated class names to more meaningful names.
* Images now have alternative text in case they don't load.  

#### CSS  
* Condensed the number of classes in use so that updates are easier to add.
* Updated class names as per the updates made to index.html so that classes are more meaningful.
* Classes follow a logical order and reflect the layout in the index.html file.
* Comments added to explain the class structures that are in use.


  
### Test Strategy:  
* Operational Acceptance Testing:  
Webpage is responsive and links work correctly. 
* User Acceptance Testing:  
Webpage meets user's needs, the interface is intuitive and meets accessibility standards.  


#

## Screenshot of finished webpage:
### URL: https://mj-0001.github.io/horiseon-code-refactor/    

![refactored code screenshot](Develop/assets/images/Horiseon_Screenshot.png)  

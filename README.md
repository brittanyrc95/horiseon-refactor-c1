
# Horiseon-Refactor-C1

Horiseon, a marketing agency, requested a refactor of their landing page codebase to meet accessibility standards and improve search engine optimization.

## Refactor Requirements
**User Story**  

    AS A marketing agency  
    I WANT a codebase that follows accessibility standards  
    SO THAT our own site is optimized for search engines.  
**Acceptance Criteria** 

    GIVEN a webpage meets accessibility standards:  
    - WHEN I view the source code, I find semantic HTML elements  
    - WHEN I view the structure of the HTML elements, I find that the elements follow a logical structure independent of styling and positioning  
    - WHEN I view the image elements, I find accessible alt attributes  
    - WHEN I view the heading attributes, they fall in sequential order  
    - WHEN I view the title element, I find a concise, descriptive title


## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility

**SEO and Accessibility**  

    1. Updated title from "webpage" to "Horiseon"
    2. Optimized for screen readers and SEO via semantic tags
    3. Fixed "Search Engine Optimization" link in nav bar
    4. Added alt attributes and text to all images

**CSS Refactors**  

    1. Organized CSS rules semantically
    2. Updated selectors to reflect semantic tags
    3. Combined all repeat font-family declarations into one under body selector
    4. Condensed style rules for content and benefits sections
## Screenshots

![App Screenshot](./assets/images/horiseon-landing-page.png)


## Demo

https://brittanyrc95.github.io/horiseon-refactor-c1/


## Lessons Learned

What did you learn while completing this assignment? What challenges did you face and how did you overcome them?  

Refactoring the codebase for the Horiseon landing page gave me the chance to practice 
reading code from another developer and identifying code that can be consolidated or optimized.
The main challenge of this assignment was ensuring that how the webpage rendered wasn't affected
by any changes made to improve accessibility and SEO or consolidate repetative code.
In order to verify that the changes being made had no affect on how the webpage was rendered, I used the Live Server
VSCode extension to immediately see the affects of any changes I made to the codebase.
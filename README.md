# Challenge-01 - HTML, CSS, and Git: Code Refactor

## Description
The purpose of this project is to perform code refactoring on the Horiseon webpage to address the following user story and acceptance criteria. Acceptance Criteria have been broken down into indidivual features (e.g. AC01). For details on each implementation, review the applicable 'AC' number in the "Features" section of this README.

### User Story

* AS A marketing agency,
I WANT a codebase that follows accessibility standards,
SO THAT our own site is optimized for search engines

### Acceptance Criteria

> * AC01: Accessibility Standards
>    - GIVEN a webpage meets accessibility standards
>    - (Apply items in “Things to always do…” in the Challenge README)

>* AC02: Semantic HTML Elements
>    -	WHEN I view the source code
>    -	THEN I find semantic HTML elements

>* AC03: Logical Structure
>    -	WHEN I view the structure of the HTML elements
>    -	THEN I find that the elements follow a logical structure independent of styling and positioning

>* AC04: Accessible alt Attributes
>    -	WHEN I view the icon and image elements
>    -	THEN I find accessible alt attributes

>* AC05: Sequential Heading Attributes
>    -	WHEN I view the heading attributes
>    -	THEN they fall in sequential order

>* AC06: Concise, Descriptive Title
>    -	WHEN I view the title element
>    -	THEN I find a concise, descriptive title


## Installation

> To launch the webpage, open the browser and paste the following URL in the address bar: <INSERT URL> 

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```

## Credits

N/A

## License

N/A


## Features

> * AC01: Accessibility Standards
>   -   Implementation:
>       -   Added an id to the Search Engine Optimization section element to fix the broken link in the nav bar


>* AC02: Semantic HTML Elements
>   -   Implementation:
>        -   Changed the "div" element to "figure" for the main image
>        -   Changed the "div class="header"" element to "header"
>        -   Renamed the ".header" style to to "header"
>        -   Renamed the ".header h1" style to "h1"
>        -   Changed the "div" element in the header for the navigation bar to "nav"
>        -   Renamed ".header div" style to "nav"
>        -   Renamed the ".header div ul" style to "ul"
>        -   Renamed the ".header div ul li" style to "li"

>* AC03: Logical Structure
>   -   Implementation
>       -   Renamed the "header h1 seo" style to "seo" to make it easier to find in the stylesheet
>

>* AC04: Accessible alt Attributes
>   -   Implementation
>

>* AC05: Sequential Heading Attributes
>   -   Implementation

>* AC06: Concise, Descriptive Title
    -   Implementation:
    -   Changed "title" element value from "Website" to "Horiseon Social Solution Services" 

    

## Tests

>1. Open the "CHALLENGE-01" repo using VSCode
>2. Inspect the "index.html" and "style.css" files to confirm all changes documented in the "Features" >section of this README have been implemented

# Code Refactoring using HTML, CSS, and Git

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

## Description 

[Visit the Deployed Site](https://aarticontractor.github.io/Code-Refactor/)

This repository "Code-Refactor" is where I as a bootcamp student, have refactored an existing peice of code in accordance with the accesibility standards.

Some aspects of the existing HTML and CSS codes were changed in order to make the page more accessible and responsive for the client.

With help from useful references and class content the refactoring was made possible. 


The main motivation for this project was to see how minute changes in the code can help discover advanced effects in the output needed. Because of this project I was able to implement the CSS styles and play along to see what difference it makes in the outcome of the project.

In the end, I have tried my best to complete the acceptance criteria based on the user story.


<br>

## Table of Contents:

* [Code Refactor Example](#code-refactor-example)
* [Usage](#usage)
* [Learning Points](#learning-points)
* [Author Info](#author-info)
* [Credits](#credits)


<br>

## Code Refactor Example

The below code shows a single class of the code and how CSS was applied later on to make it responsive.

```html
<div id="search-engine-optimization" class="search-engine-optimization">
    <!--Add Alt attributes to images-->
    <img src="./assets/images/search-engine-optimization.jpg" alt="SEO diagram in notebook" class="float-left" />
    <h2>Search Engine Optimization</h2>
    <p> The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business. </p>
</div>
```


The below code snippet shows the media query inserted for the above code of search engine optimisation class to make it responsive for devices smaller than 780 pixels.



```css
@media screen and (max-width: 780px) {

    .search-engine-optimization, .online-reputation-management, .social-media-marketing {
        margin-bottom: 5px;
        padding: 5px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        background-color: #0072bb;
        color: #ffffff;
        flex-direction: column;
        
    }
    .search-engine-optimization img {
        max-height: 120px;
    
   }
}
```


<br>


## Usage 



For example, when the SEO link was unable to redirect on the page to its content, the code was refactored and thus the solution has been provided in the below GIF:


![alt text](./assets/images/horiseon.gif)

<br>

## Learning Points 

I learned the following skills while doing this project:

- Using Command line to navigate and create repositories in GitHub
- Semantic elements of HTML
- Advanced properties of CSS (styling, display, text, flexbox,media query, etc) to make the page responsive.
- The Git flow (clone, add, commit, push, pull, etc)
- Using debugging skills to point out small issues in the code provided
- Made use of Google DevTools 

<br>

## Author Info


### Aarti Contractor


- Linkedin: https://www.linkedin.com/in/aarti-contractor/
- Github: https://github.com/aarticontractor


<br>

## Credits

The following resources were used while making this project:


- https://www.w3schools.com/
- https://developer.mozilla.org/en-US/




© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
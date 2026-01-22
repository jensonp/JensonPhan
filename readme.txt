--Readme document for *YOUR NAME*, *YOUR_EMAIL@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

HTML: 
There is an image of an egg at the bottom of the site that links to a Youtube video. 
There are heading elements <h1>, and <h2> to signify the title, resume, and github link.
The "Resume" text links to a PDF of my resume. 
The "Github" text links to my Github profile.
There are 3 <a> elements for the 3 social media accounts in the navigation bar. 
A short <p> element only introduces my name, school, and degree. 
A footer exists at the bottom of the site. 
A flavicon of a vampire exists.


(b) CSS features

The elements are displayed, and positioned via flex. 
The margin, border, and padding of the text elements have appropriate values.
There exists @media rule for the responsiveness requirement.  
Links are void of their blue color, and underline appearance.
Hovering over a clickable link creates an animated color transition using cubic-bezier. 
There is a custom google font, Sansita, as well as a fall back to sans serif. 

(c) Advanced features

A navigation bar at the top of the page links to outgoing social media accounts. 
Using Typed.js, specific text elements appear sequentially in an animated fashion. 
There is a video of a revolving red earth with fallbacks, but only text to show that the video isn't available.


3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
I list the check or multiple checks, and then provide a one sentence reasoning below them. 

1.1 Text Alternatives: Provide text alternatives for any non-text content
It is useful to provide a description for what the image is linking is linking to. 

Success Criteria 1.3.1 Info and Relationships (A)
I don't need to identify the text direction, because I specified that the language is english in the html element. 

Success Criteria 1.3.3 Sensory Characteristics (A)
Check 271: dir attribute may be required to identify changes in text direction.
Check 270: Unicode right-to-left marks or left-to-right marks may be required.
Since the language english is specified in the html element, it is implied that the text direction is from left to right. 

Check 248: Visual lists may not be properly marked.
The syntax for the creation of my list is correct.

Success Criteria 1.3.3 Sensory Characteristics (A)
Check 250: Text may refer to items by shape, size, or relative position alone.
I have no text that describes clicking in a specific direction or location. 

Success Criteria 1.4.1 Use of Color (A)
Check 14: Image may be using color alone.
Check 251: Image may contain text with poor contrast.
It is an image of an egg that is suppose to semantically mean an easter egg, so no text should appear.
The image is only meant for people who are curious enough to click the image.

Check 86: script may use color alone.
The Typed.js script doesn't convey an image/message with only color. 

Success Criteria 1.4.5 Images of Text (AA)
Check 11: Image may contain text that is not in Alt text.
The egg does not have any text. 

2.1 Keyboard Accessible: Make all functionality available from a keyboard.
Success Criteria 2.1.1 Keyboard (A)
Check 89: script user interface may not be accessible.
You are still able to reach every clickable/downloadable button with the keyboard by using Tab.
The Typed.js doesn't affect the ability for tab to do it's job to navigate around the site. 

2.3 Seizures: Do not design content in a way that is known to cause seizures.
Success Criteria 2.3.1 Three Flashes or Below Threshold (A)
Check 87: script may cause screen flicker.
Typed.js does not create any flickering effect.

2.4 Navigable: Provide ways to help users navigate, find content, and determine where they are.
Success Criteria 2.4.1 Bypass Blocks (A)
Check 262: Groups of links with a related purpose are not marked.
There is an aria label to describe that the links are social media links.

Success Criteria 2.4.2 Page Titled (A)
Check 54: title might not describe the document.
My title "Jenson Phan Portfolio" properly describes the document. 

Success Criteria 2.4.4 Link Purpose (In Context) (A)
Check 19: Link text may not be meaningful.
All of the links are self-intuitive, except for the egg which was an intentional design. 

Success Criteria 2.4.5 Multiple Ways (AA)
Check 184: Site missing site map.
This is the only page of my site, so there is no need to create a site map. 

Success Criteria 2.4.6 Headings and Labels (AA)
The headings <h1> and <h2> in my document convey document structure. 

3.1 Readable: Make text content readable and understandable.
Success Criteria 3.1.2 Language Parts (AA)
Check 110: Words or phrases that are not in the document's primary language may not be identified.
English is the only language in this document. 

3.2 Predictable: Make Web pages appear and operate in predictable ways.
Success Criteria 3.2.3 Consistent Navigation (AA)
The components do not have any impact. 

Check 276: Repeated components may not appear in the same relative order each time they appear.
The repeated components appear in the same relative order, so this passes. 

Check 131: Long quotations may not be marked using the blockquote element.
This is not an issue because I only one <p> element for my long sentence, so I don't necessarily need a blockquote element to wrap it. 

4. How long, in hours, did it take you to complete this assignment?

At least 25 hours. 

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

I used this site as inspiration: https://neo-tokyo.webflow.io/

The main source of information derived from Mozilla's HTML tutorials and CSS tutorials.
I used the W3 specifications, chapters 8-10 to learn about the box model, and formatting contexts. 

https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Basic_concepts
https://github.com/mattboldt/typed.js
https://www.w3schools.com/html/html_favicon.asp
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@media 
https://www.w3schools.com/css/css3_fonts.asp 
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_images 
https://www.w3.org/TR/CSS2/box.html 
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model
https://www.w3.org/TR/2011/WD-html5-20110405/ 
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/easing-function/cubic-bezier 
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:hover 
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Transitions/Using 
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Selectors
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics
https://forum.freecodecamp.org/t/before-after-box-sizing-border-box/425735 
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA
https://www.w3schools.com/accessibility/accessibility_skip_links.php 
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Attributes/rel/noopener 
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/footer 

There are many more links I have visited, however, I would have to dig through them all and paste them here, 
so I just picked the most notable links in my history for brevity. 

I used generative AI to aid me in 
-modifying the main and sub classes to fix the flex component's direction, alignment, and justification
-determine where and what aria labels to place
-creating an inline element fix to not show duplicate Github text
-creating an css rule for the "hidden" class to aid in hiding the Github text
-creating a css rule for the video element to comply with responsiveness
-determining what and where to place the <a> and <main> element to create the
ability to skip to the main content of the page
-including a rel attribute in the <a> tag that refers to the egg image 
-finding a generic rule to fix the box size 
```*,
*::before,
*::after {
    box-sizing: border-box;
```
-fixing overflow in for class="main" in the css rule


6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

No one. 

7. Is there anything special we need to know in order to run your code?

No. 
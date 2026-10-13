--Readme document for *Daniel Ho Kim*, *danihk15@uci.edu*

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
- Used Headings and paragraphs to introduce myself and projects
- Added Maroom project image with alt text
- Included external link to my github, project, and email 
- Used semantic HTML elements: header, nav, main, article, etc.

(b) CSS features
- Changed Colors of headings, background, and links
- Used margin, padding, borders, border radius for specific spacing and layout
- Styled navigation and project links including hover effects
- Used media queries to change the layout when screens are smaller


(c) Advanced features
- Created navigation bar that leads to Home, About, Projects, Contact
- Used nested CSS selectors: nav a and article a



3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
- WAVE: No, I did not ignore any of the warnings or errors presented by the accessibility checker.
- AChecker: Yes, only for the potential problems. 
Fixed: 1. It said to add a "Skip to main content" for the keyboard users, so I added link at the top of <body> in index.html.
       2. Added id="main-content" to the <main> so that the skip link goes directly to main content.
       3. Added .skip-link and .skip-link:focus styles in style.css so the link is hidden and only appears when tab is pressed.
Ignored: - 8, 11, 14, 16, 178, 251: The logo's alt text accurately describes it, so I could just ignore these problems
         - 110, 270, 271: The only used language is English, so I could ignore these problems.
         - 19, 54: Link text and the page title are descriptive.
         - 42, 43, 44, 248, 262: Headings, lists, and the <nav> element are used for structure.
         - 131, 184, 250, 276: Single-page site with no quotes or position-based instructions.

4. How long, in hours, did it take you to complete this assignment?
- It approximately took 6 hours to complete this assignment


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
- W3C HTML Validator: https://validator.w3.org/
- W3C CSS Validator: https://jigsaw.w3.org/css-validator/
- WAVE Accessibility Evaluation Tool: https://wave.webaim.org/
- AChecker Web Accessibility Checker: https://achecks.org/achecker/
- IN4MATX 133 lecture slides for HTML, CSS, responsive design, and accessibility.
- Claude (Generative AI, https://claude.ai): I used Claude to check what potential problem that I could fix from AChecker result. It suggested adding a "Skip to main content" link and provided the HTML and CSS code (.skip-link and .skip-link:focus), which I added to index.html and style.css. Fixed part is helped by Claude. I also asked about what can be ignored. Being honest, based on my current knowledge in HTML and CSS, I couldn't resolve any of the potential problems that came up in AChecker website, so I had to ask Claude what I can fix and what I can ignore. I asked Claude to learn more about the potential error.


6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
- I talked with one of my graduate friend Jaemin Park, who is a computer science major. He helped me in coding when I first came to UCI. He also had his own project page about his own portfolio, so he advised me in how to organize and design my portfolio page.


7. Is there anything special we need to know in order to run your code?
- No special setup is required. 

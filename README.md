# TOP-Project1-LandingPage
Foundations Course Project 1 - Landing Page

Keep notes of what I learned during this project, and also, things to keep in mind.

## div needs content for css to be applied

- If the div container has no sizeable content, then it will not consume any space on the page. 
- For example, if you try to apply 'background-color' to an empty 'div' container, it will not show on the page.
- You can specify the height (and or width) of the container for the bg-color to show on the page.
- Or if the container has some elements, such as buttons, inputs, or 'ul' with 'li' that have bullets for list style, these elements will consume space on the page by default, and the css will be applied accordingly.

## Establish a workflow

- It was incredibly frustrating when starting this project.
- It was fine while working on index.html.
- It started to become very chaotic when I was adding the styles.
- I needed another div here and there, I don't need that here.
- Every time I changed the html structure, the css went out the window.

- Also, adding margins and padding to elements quickly became 'untrackable'.
- How does this padding affect this element? Do I need this margin here at all?
- Most of the time, the margins and paddings became redundant and unnecessary.
- Finally figured out that it works well if I work on one section at a time, top to bottom.
- For each section, work from outside to inside, keeping track of all the flex containers and flex items.

- I guess it will become more comfortable with repetitive practice.

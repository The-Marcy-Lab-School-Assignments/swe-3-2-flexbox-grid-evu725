# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**Your Answer:**
A **flex container** is the parent element that gets the `display: flex`. A **flex-item** is the children of the flex container.

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**Your Answer:**
The **main axis** is defined by the flex-direction property. The **cross axis** is perpendicular to the flex-direction. The `justify-content` is the alignment along the main axis and the `align-items` is the alignment along the cross-axis. 

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**Your Answer:**
I would use **Grid** because it's super easy to use compared to **Flexbox**. **Grid** is best use for content that fits into even, consistent sections, and when it's needed for layouts, **Flexbox** is best use for elements that need more flexibility and do not fit into a strict grid, and is works well for individual components.

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**Your Answer:**
The `fr` unit divides the remaining available space in the grid after everything else is calculated. The grid is divided into three columns from the fractional units. The total space is split into four parts and the second column takes up two of those parts, making it twice as wide as the first and third columns.

## Question 5: Media Queries
What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**Your Answer:**
**Media query** applies styles based on the user's device and it helps with creating responsive designs because it allows the layout and appearance of the website adapt to different devices. 

```js
/* When the browser is at least 768px and above */ 
@media (min-width: 768px) {
    .container {
        grid-template-columns: repeat(2, 1fr);        
    }
}
```

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Your Answer:**

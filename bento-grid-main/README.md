📌 Bento Grid UI

A clean, modern, responsive Bento Grid layout built using HTML & CSS.
This project is inspired by a Frontend Mentor challenge and focuses on creating flexible bento-style cards using CSS Grid, Flexbox, and mobile-first responsive design.

📚 Table of Contents

Overview

The challenge

Screenshot

Links

My process

Built with

What I learned

Continued development

Useful resources

Author

Acknowledgments

🌟 Overview

This project recreates a Bento Grid UI similar to those used in dashboards, SaaS platforms, and modern marketing landing pages.
The layout consists of cards in different shapes and sizes arranged using CSS Grid with 6 invisible columns for precise control.

The purpose of this project was to strengthen my skills in:

Advanced CSS Grid layouting

Mobile responsiveness

UI spacing, alignment, and styling

Combining Grid + Flexbox for inner and outer structure

🚀 The challenge

Users should be able to:

View the layout perfectly on desktop, matching the bento-style design

Experience a clean mobile layout where all cards stack full-width

See balanced spacing, consistent alignment, and smooth responsive behavior

Understand how CSS Grid spanning is used to create non-uniform card sizes

🖼️ Screenshot

design/Desktop_design_screenshot.jpeg

🔗 Links

🧾 Solution Repository:
https://github.com/John-Uko/Bento-Grid.git

🌍 Live Site:


🛠️ My process
🔧 Built with

Semantic HTML5

CSS Grid (repeat, auto rows, spanning)

Flexbox for inner card alignment

Custom variables (optional)

Mobile-first responsive design

Bento UI design pattern

📚 What I learned

This project taught me several valuable CSS concepts:

🎯 1. Why a 6-column grid is needed

Even though the design looks like 3 columns, using 6 smaller grid columns provides finer control, allowing cards to span:

1 column

2 columns

3 columns

and combine in any pattern

🎯 2. Row/column spanning

I used:

grid-column: span X;
grid-row: span Y;


to control card sizes perfectly.

🎯 3. Default Grid behavior

I learned that CSS Grid automatically flows items into new rows, even without:

grid-auto-flow: row;


because row-flow is the default.

🎯 4. Mobile responsiveness using Grid

By switching the grid to a single column on mobile:

@media (max-width: 768px) {
  .grid {
    grid-template-columns: 1fr;
  }
}


every card becomes full width.

🎯 5. Combining Grid + Flexbox

Grid handles layout structure, while Flexbox handles content alignment inside each card.

🔄 Continued development

Future improvements I plan to work on:

Convert the entire layout to Tailwind CSS

Add animations on hover and scroll

Rebuild this layout using React components

Add dark mode

Increase reusability for dashboard UI templates

🧩 Useful resources

W3School: The Complete Guide to Grid – My go-to reference while building

Frontend Mentor – Project inspiration and UI design samples


👤 Author

John Uko

GitHub: https://github.com/John-Uko

Frontend Mentor: https://www.frontendmentor.io/profile/John-Uko

🙏 Acknowledgments

Special appreciation to the Frontend Mentor community for inspiring the design style and helping me practice real-world layout challenges.
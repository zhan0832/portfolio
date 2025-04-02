# Portfolio

## Process
Creating my web portfolio was a structured process that involved planning, designing, and coding. I started by sketching out a basic wireframe to determine the layout and structure. After finalizing the design concept, I used Bootstrap to implement a responsive and clean interface.

## Challenges & Solutions
- **CSS Adjustments with Bootstrap**: Initially, modifying Bootstrap’s default styles was challenging, as finding the exact CSS property to override required inspecting elements. I overcame this by using browser developer tools (Inspect Element) to locate and apply precise CSS modifications.
- **Customization Limitations**: While Bootstrap made basic layout implementation easier, achieving a more unique and customized look required additional CSS. I had to add extra custom styles to override default Bootstrap classes and make the design stand out.
- **Validate My CSS Code**: My initial design style featured light orange and blue, but the colors failed to meet contrast accessibility standards. It took a lot of time to find similar colors that maintained the intended aesthetic while passing contrast validation.

## Lessons Learned
- **Bootstrap is great for quick layouts**: My portfolio follows a simple layout, and Bootstrap made it easy to set up the grid system and responsive design.
- **Customization requires additional effort**: For more complex designs or unique branding, Bootstrap alone is not enough. It often requires a mix of custom CSS and HTML class modifications.
- **Inspect Element is a powerful tool**: Debugging and styling became more efficient by utilizing the browser's Inspect Element feature to understand Bootstrap’s class structure.

## Resources & Assets Used
- **Frameworks & Libraries**:
  - [Bootstrap 5.3.3](https://getbootstrap.com/)
  - [Bootstrap Icons](https://icons.getbootstrap.com/)
- **CDN Links Used**:
  ```html
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <!-- Bootstrap Icons -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
  ```
- **Fonts & Images**:
  - `my-picture.jpg` from [Pixabay](https://pixabay.com/)
  - Font: [Penn Station](https://fonts.cdnfonts.com/css/penn-station) (imported via `@import url('https://fonts.cdnfonts.com/css/penn-station');`)
  - Design: [Figma Project](https://www.figma.com/design/W2Ng0ucZI9pBHQflM9mBoH/Sitemap-and-User-Journey-Map?node-id=151-78&t=LKWMXLb3PHL2jMxX-1)

## Future Improvements
- Implementing a more unique design by reducing reliance on Bootstrap defaults.
- Exploring alternative frameworks such as Tailwind CSS for greater flexibility.
- Adding animations and interactive elements to enhance user experience.

---
This portfolio project has been a valuable learning experience, allowing me to apply my web development skills and understand the strengths and limitations of using Bootstrap for front-end design.
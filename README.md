Pricing Table Project

This project is a responsive pricing table built using HTML5 and CSS3 Flexbox. It features a clean, modern design that adapts seamlessly to different screen sizes, ensuring a consistent user experience on both desktop and mobile devices.
🚀 Features

    Responsive Design: Utilizes CSS Media Queries to switch from a horizontal layout on large screens to a vertical stack on mobile devices.

    Flexbox Layout: Leverages display: flex for easy alignment, centering, and spacing of pricing cards.

    Custom Typography: Integrated with Google Fonts using the "Sono" typeface for a unique, technical look.

    Interactive Elements: Includes styled buttons with hover-ready states and clear visual hierarchy for pricing tiers.

🛠️ Technologies Used

    HTML5: For semantic structure.

    CSS3: Including Flexbox, Media Queries, and custom styling.

    Google Fonts: "Sono" font family.

📸 Screenshots
Desktop View

The pricing plans are displayed side-by-side to take advantage of wide viewports.
Mobile View

The cards stack vertically for readability on smaller screens (triggered at a breakpoint of 1250px).
📂 Project Structure

    index.html: Contains the HTML structure and internal CSS styling.

    goal-large.jpg: Reference image for the desktop layout design.

    goal-small.jpg: Reference image for the mobile layout design.

⚙️ Key Styling Details

The project uses a container-based approach to manage the layout:
CSS
```
.pricing-container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 2rem;
  height: 100vh;
}
```

To handle responsiveness, the layout flips the flex direction:
CSS
```

@media (max-width: 1250px) {
  .pricing-container {
    flex-direction: column;
    height: 100%;
  }
}
```

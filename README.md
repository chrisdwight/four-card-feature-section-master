# Four Card Feature Section

A responsive webpage showcasing four feature cards with a modern design and unique layout arrangement.

## Description

This project presents a clean and professional four-card layout featuring different technology services. The design uses a unique grid arrangement where the outer cards (Supervisor and Calculator) are vertically centered, while the middle cards (Team Builder and Karma) are stacked on top of each other.

## Features

- **Responsive Design**: Adapts seamlessly from desktop to mobile devices
- **Modern Card Layout**: Clean cards with colored top borders and SVG icons
- **CSS Grid Implementation**: Uses CSS Grid for precise positioning and layout control
- **Mobile-First Approach**: Single column layout on mobile devices for optimal readability
- **Typography**: Uses Poppins font family for a modern, professional look

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- CSS Flexbox
- Google Fonts (Poppins)
- SVG Icons

## Layout Structure

### Desktop Layout
- Three-column grid layout
- Supervisor and Calculator cards positioned with vertical offset
- Team Builder and Karma cards stacked in the center column
- Each card features a colored top border and positioned SVG icon

### Mobile Layout
- Single column stack
- Equal spacing between all cards
- Maintains card proportions and readability

## Key CSS Techniques

**Grid Layout:**
```css
.main {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 20px;
    align-items: start;
}
```

**Card Positioning:**
```css
.supervisor, .calculator {
    transform: translateY(100px);
}
```

**Responsive Design:**
```css
@media (max-width: 700px) {
    .main {
        grid-template-columns: 1fr;
    }
}
```

## File Structure

```
four-card-feature-section/
├── index.html
├── style.css
├── README.md
└── design/
    └── (design reference files)
```

## Getting Started

1. Clone or download the project files
2. Open `index.html` in your web browser
3. Resize the browser window to see the responsive behavior

## Browser Compatibility

This webpage is compatible with all modern browsers that support CSS Grid and Flexbox.

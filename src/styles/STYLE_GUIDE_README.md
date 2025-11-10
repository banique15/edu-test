# Sing for Hope Classroom Style Guide

This directory contains the complete style guide for the Sing for Hope Classroom website, including all design tokens, typography, colors, and component styles.

## Files Structure

- `style-guide.html` - Complete visual style guide document
- `style-guide.css` - All CSS styles and design tokens
- `STYLE_GUIDE_README.md` - This documentation file

## Quick Start

To view the style guide, open `style-guide.html` in your browser. The CSS file contains all the reusable styles and design tokens that can be imported into your project.

## Design System Overview

### Brand Colors

The style guide includes a comprehensive color system with CSS custom properties:

```css
:root {
  --SFH-Green: #349552;
  --SFH-White: white;
  --SFH-Black: black;
  --SFH-Cream: #FDF9F1;
  --SFH-Cream-Dark: #EEEAE5;
}
```

### Sustainable Development Goals Colors

All 17 SDG colors are included as CSS variables:

```css
--01_No-Poverty: #E5243B;
--02_Zero-Hunger: #DDA63A;
--03_Good-Health-Wellbeing: #4C9F38;
/* ... and 14 more */
```

### Typography

The style guide uses **Founders Grotesk** as the primary typeface with the following hierarchy:

- **Display**: 84px, Medium weight, -2.5px tracking, 90% line height
- **H1**: 60px, Regular weight, -1px tracking, 90% line height
- **H2**: 48px, Regular weight, -1px tracking, 90% line height
- **H3**: 32px, Regular weight, -1px tracking, 90% line height
- **H4/H5**: 28px, Medium weight, -1px tracking, 90% line height
- **H6**: 20px, Medium weight, 0px tracking, 120% line height
- **Subhead**: 14px, Medium weight, ALL-CAPS, 5px tracking, 120% line height
- **Body Large**: 24px, Regular weight, 0px tracking, 130% line height
- **Body**: 18px, Regular weight, 0px tracking, 120% line height
- **Body Small**: 16px, Regular weight, 0px tracking, 120% line height

### Typography CSS Classes

Use these classes for consistent typography:

```css
.type-display { /* 84px display text */ }
.type-h1 { /* 60px heading */ }
.type-h2 { /* 48px heading */ }
.type-h3 { /* 32px heading */ }
.type-h4, .type-h5 { /* 28px heading */ }
.type-h6 { /* 20px heading */ }
.type-subhead { /* 14px uppercase subheading */ }
.type-body-large { /* 24px body text */ }
.type-body { /* 18px body text */ }
.type-body-small { /* 16px body text */ }
```

## Components

### Rounded Rectangles

Used throughout the site for content organization:

```css
.rounded-rect {
  border-radius: 20px;
  padding: 20px;
}

.rounded-rect-solid {
  background-color: var(--SFH-Green);
  color: white;
}

.rounded-rect-outline {
  background-color: white;
  border: 1.5px solid var(--SFH-Green);
  color: var(--SFH-Black);
}
```

### Pill Shapes

Used for labels and filters:

```css
.pill {
  border-radius: 50px;
  padding: 6px 14px;
  font-size: 16px;
  display: inline-flex;
  align-items: center;
  gap: 6px;
}

.pill-default {
  background-color: var(--SFH-Green);
  color: white;
}

.pill-outline {
  background-color: transparent;
  border: 1.5px solid black;
  color: black;
}
```

### SDG Goal Pills

Each Sustainable Development Goal has its own pill style:

```css
.pill-goal-1 { background-color: var(--01_No-Poverty); color: white; }
.pill-goal-2 { background-color: var(--02_Zero-Hunger); color: black; }
/* ... continues for all 17 goals */
```

## Usage in Svelte Components

### Importing Styles

Add this to your Svelte component's style section:

```svelte
<style>
  @import '../styles/style-guide.css';
  
  /* Your component-specific styles */
</style>
```

### Using Design Tokens

```svelte
<style>
  .my-component {
    background-color: var(--SFH-Green);
    color: var(--SFH-White);
    border-radius: 20px;
    padding: 20px;
  }
</style>
```

### Using Typography Classes

```svelte
<h1 class="type-h1">Main Heading</h1>
<h2 class="type-h2">Section Heading</h2>
<p class="type-body">Body text content</p>
<span class="type-subhead">Subheading</span>
```

### Using Component Classes

```svelte
<!-- Rounded rectangle with solid background -->
<div class="rounded-rect rounded-rect-solid">
  <h3 class="type-h3">Content Title</h3>
  <p class="type-body">Content description</p>
</div>

<!-- Pill for SDG Goal 4 -->
<span class="pill pill-goal-4">4. Quality Education</span>

<!-- Default pill -->
<span class="pill pill-default">Filter Label</span>
```

## Color Swatches

The style guide includes utility classes for displaying color swatches:

```css
.color-swatch { /* Base swatch styling */ }
.swatch-sfh-green { background-color: var(--SFH-Green); }
.swatch-cream { background-color: var(--SFH-Cream); }
.swatch-cream-dark { background-color: var(--SFH-Cream-Dark); }
.swatch-white { background-color: var(--SFH-White); }
.swatch-black { background-color: var(--SFH-Black); }
```

## Responsive Design

The style guide includes responsive breakpoints:

- Desktop: 1280px and above
- Tablet: 768px to 1279px  
- Mobile: Below 768px

## Building Blocks Pattern

The style guide includes a playful building block pattern used for special sections like the home page and lesson page headers. This uses rounded rectangles with 20px corner radius and 10px spacing between shapes.

## Iconography

The style guide references two icon systems:

1. **Sustainable Development Goals Icons** - Official UN SDG icons for goal overview pages
2. **Lesson Icons** - Google Material Symbols icons (40dpi, weight 400) for instructional content

## Best Practices

1. **Always use CSS custom properties** for colors instead of hardcoded hex values
2. **Use the typography classes** for consistent text styling
3. **Maintain 20px border radius** for rounded rectangles
4. **Use appropriate contrast ratios** - some SDG colors require white text, others require black text
5. **Follow the component patterns** for pills, cards, and other UI elements

## Integration with Existing Project

To integrate this style guide with your existing Svelte project:

1. Import the CSS variables into your global CSS file
2. Update your existing components to use the design tokens
3. Replace hardcoded colors and typography with the style guide classes
4. Use the component patterns for new UI elements

## Maintenance

When updating the style guide:

1. Update both the HTML and CSS files
2. Test all components with the new styles
3. Update this documentation if new patterns are added
4. Ensure responsive design still works across all breakpoints

This style guide serves as the single source of truth for all design decisions in the Sing for Hope Classroom website.
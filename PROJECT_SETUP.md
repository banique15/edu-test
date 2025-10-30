# Sing for Hope Classroom - Svelte + TypeScript Project

## Project Overview
This is a Svelte + TypeScript implementation of the Sing for Hope Classroom home page design.

## Project Structure
```
edu-test/
├── src/
│   ├── lib/
│   │   └── Home.svelte          # Main home page component
│   ├── styles/
│   │   └── global.css           # Global styles and CSS variables
│   ├── App.svelte               # Root component
│   ├── app.css                  # Base application styles
│   └── main.ts                  # Application entry point
├── index.html                   # HTML entry point
├── package.json                 # Dependencies
└── vite.config.ts              # Vite configuration
```

## Setup Instructions

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Development Server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### 3. Build for Production
```bash
npm run build
```

### 4. Preview Production Build
```bash
npm run preview
```

## Design Implementation

### Color Variables
The project uses CSS custom properties for colors:
- `--SFH-White`: white
- `--SFH-Black`: black
- `--SFH-Green`: #349552
- `--SFH-Cream`: #FDF9F1
- Global Goals colors (17 colors for UN Sustainable Development Goals)

### Typography
The design uses "Founders Grotesk" font family with various weights and sizes. System fonts are used as fallback during development.

**Text Styles Include:**
- Hero title: 84px, weight 400
- Section titles: 60px, weight 400
- Goal numbers: 52px, weight 400
- Goal titles: 24px, weight 500
- Navigation items: 20px, weight 400
- And many more...

### Components Structure

#### Home.svelte
The main home page component includes:
1. **Navigation Header** - Top navigation with logo, menu items, and sign-in
2. **Hero Section** - Main headline and subtitle
3. **Global Goals Section** - 17 UN Sustainable Development Goals cards
4. **Lessons by Subject** - Subject categories display
5. **Lessons by Grade** - Grade level selection
6. **FAQ Section** - Frequently asked questions
7. **Footer** - Site links and organization information

### Responsive Design Notes
The current implementation uses fixed pixel values from the Figma design. For production, these should be converted to responsive units (rem, %, vw/vh) for better mobile support.

## Next Steps

### Required Enhancements:
1. **Add SVG Icons** - Import and add all the vector graphics for:
   - Logo elements
   - Goal icons
   - Decorative elements
   - Arrows and UI elements

2. **Add Images** - Replace placeholder images with actual assets:
   - Subject section images
   - Hero background
   - Footer logo

3. **Add Interactivity**:
   - FAQ accordion functionality
   - Navigation menu interactions
   - Button hover states and click handlers
   - Goal card hover effects

4. **Responsive Design**:
   - Add media queries for mobile/tablet views
   - Convert fixed widths to flexible units
   - Adjust typography for smaller screens

5. **Font Integration**:
   - Add Founders Grotesk font files or CDN link
   - Add Proxima Nova for copyright text

6. **Accessibility**:
   - Add ARIA labels
   - Ensure keyboard navigation
   - Add alt text for images
   - Improve color contrast where needed

7. **Routing** (if needed):
   - Add Svelte routing for multiple pages
   - Create curriculum, about, and other pages

## Technologies Used
- **Svelte 5** - Component framework
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **CSS3** - Styling with custom properties

## Browser Support
Modern browsers with CSS Grid and Custom Properties support:
- Chrome/Edge 88+
- Firefox 85+
- Safari 14+

## Notes
- The design is currently implemented with absolute positioning as per the Figma export
- For production, consider refactoring to use Flexbox/Grid for better maintainability
- Images are using placeholder URLs and should be replaced with actual assets
- SVG icons need to be added from the Figma design
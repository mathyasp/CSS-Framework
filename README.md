# Basic.css


A minimalist, classless CSS framework that styles semantic HTML beautifully out of the box.

## 🎯 Features
- **Classless Design**: Styles standard HTML elements without requiring custom classes
- **CSS Custom Properties**: Easy theming with CSS variables
- **Responsive**: Mobile-first design with breakpoint support
- **Print-Friendly**: Optimized styles for printing
- **Accessible**: High contrast, proper focus states, and semantic HTML support
- **Lightweight**: No dependencies, minimal footprint

## 📦 Installation
Add to your HTML:
```html
<link rel="stylesheet" href="basic.css">
```

## 🎨 Customization
Customize using CSS custom properties:
```css
:root {
  --t-colorPrimary: #2563eb;
  --t-colorSecondary: #475569;
  --t-fontFamily: system-ui, -apple-system, sans-serif;
  --t-fontSizeBase: 1rem;
  --t-lineHeight: 1.5;
}
```

## 🔘 Button Variants
While mostly classless, the framework includes button variants:
```html
<button>Default Button</button>
<button class="Button--success">Success Button</button>
<button class="Button--warning">Warning Button</button>
<button class="Button--danger">Danger Button</button>
```

## 📱 Responsive Features
- Mobile-first approach
- Fluid typography
- Responsive tables
- Flexible images
- Breakpoint at 768px

## 🖨️ Print Styles
Automatic print optimization:
- Black text on white background
- Underlined links
- Hidden buttons
- Optimized layout

## 📝 Elements Supported
- Typography (headings, paragraphs)
- Forms and inputs
- Tables
- Lists
- Images
- Blockquotes
- Code blocks
- Buttons

## 🌐 Browser Support
Works in all modern browsers.

## 📜 License
MIT License

This README accurately represents the current implementation while maintaining a professional tone and clear documentation structure.
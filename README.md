﻿# 🎨 ALX Intermediate Frontend Projects

This repository contains two main projects demonstrating different aspects of modern web development:

## 📚 Projects Overview

### 1. 📝 Semantic HTML (0x00-semantic_html)
A project focusing on creating well-structured HTML documents using semantic elements for better accessibility and SEO.

#### Key Features:
- 🏗️ Proper HTML5 document structure
- 🔍 SEO-optimized meta tags
- ♿ Accessibility-focused elements
- 📄 Semantic layout components
- 📝 Blog post structure
- 📋 Accessible forms with ARIA attributes

#### Files:
- `0-index.html`: Basic semantic structure
- `1-index.html`: Enhanced with meta tags
- `2-index.html`: Blog post layout
- `3-index.html`: Accessible form implementation

### 2. 🎨 Tailwind CSS (0x02-tailwind-css)
A project showcasing various layouts and components built using Tailwind CSS.

#### Key Features:
- 📱 Responsive designs
- 🎯 Grid layouts
- 🔄 Flexbox implementations
- 🖼️ Image galleries
- 📊 Complex nested layouts

#### Files:
- `1-index.html`: Basic CSS Grid Layout
- `2-index.html`: Complex Grid Layout
- `3-nav_index.html`: Flexbox Navigation
- `4-flexbox_index.html`: Responsive Flexbox Layout
- `5-gridflex_index.html`: Combined Grid and Flexbox
- `6-imageGallery.html`: Image Gallery

## 📁 Project Structure

### Semantic HTML
```
0x00-semantic_html/
├── 0-index.html
├── 1-index.html
├── 2-index.html
└── 3-index.html
```

### Tailwind CSS
```
0x02-tailwind-css/
├── src/
│   ├── input.css
│   └── output.css
├── tailwind.config.js
├── 1-index.html
├── 2-index.html
├── 3-nav_index.html
├── 4-flexbox_index.html
├── 5-gridflex_index.html
└── 6-imageGallery.html
```

## 🚀 Setup Instructions

### Prerequisites
- 📥 Node.js and npm installed
- 🌐 Modern web browser
- 📝 Code editor

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yamneg96/alx-intermediate-frontend
   ```

2. **For Tailwind CSS Project**
   ```bash
   cd 0x02-tailwind-css
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss -i ./src/input.css -o ./src/output.css
   ```

## 💻 Usage

### Semantic HTML
- Open any HTML file in the `0x00-semantic_html` directory
- Inspect the semantic structure using browser dev tools
- Test accessibility using screen readers
- Validate HTML using W3C validator

### Tailwind CSS
- Navigate to `0x02-tailwind-css` directory
- Run the Tailwind build process:
  ```bash
  npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
  ```
- Open HTML files in your browser
- Resize window to see responsive designs

## 📝 Notes

- ⚡ Keep Tailwind CSS build process running during development
- 🔄 Output CSS is generated automatically
- 📱 All layouts are responsive and mobile-friendly
- ♿ Semantic HTML improves accessibility and SEO
- 🎯 Each project demonstrates different aspects of modern web development

## 🎯 Learning Objectives

### Semantic HTML
- Understanding semantic HTML elements
- Implementing accessible web forms
- Creating SEO-friendly structures
- Using ARIA attributes
- Building accessible content
- Following HTML5 best practices

### Tailwind CSS
- Creating responsive layouts
- Implementing grid systems
- Using flexbox for navigation
- Building complex nested layouts
- Creating image galleries
- Mobile-first design approach

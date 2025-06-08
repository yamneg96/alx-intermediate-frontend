# 🎨 Tailwind CSS Project

This project demonstrates various layouts and components built using Tailwind CSS, including grid layouts, flexbox navigation, and responsive designs.

## 📁 Project Structure

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

1. **📥 Install Node.js and npm**
   - Make sure you have Node.js and npm installed on your system
   - You can download them from [nodejs.org](https://nodejs.org/)

2. **📦 Install Dependencies**
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   ```

3. **🔨 Build CSS**
   - The project uses Tailwind CSS for styling
   - To build the CSS, run:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css
   ```
   - For development with auto-rebuild:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

## 📄 Project Files

1. **📊 1-index.html**: Basic CSS Grid Layout
   - Demonstrates a simple 3-column grid layout
   - Responsive design that adjusts to screen size

2. **🔷 2-index.html**: Complex Grid Layout
   - Shows nested grid layouts
   - Uses different background colors for visual hierarchy

3. **🔗 3-nav_index.html**: Flexbox Navigation
   - Responsive navigation bar using Flexbox
   - Adjusts to mobile view on smaller screens

4. **📱 4-flexbox_index.html**: Responsive Flexbox Layout
   - Uses Tailwind CDN for styling
   - Demonstrates sidebar and content layout

5. **🎯 5-gridflex_index.html**: Combined Grid and Flexbox
   - Shows how to combine grid and flexbox layouts
   - Responsive design with breakpoints

6. **🖼️ 6-imageGallery.html**: Image Gallery
   - Responsive image grid layout
   - Uses CSS Grid for image arrangement

## 💻 Usage

1. Open any of the HTML files in your browser to see the layouts
2. Resize your browser window to see the responsive design in action
3. Inspect the elements to see how Tailwind CSS classes are used

## 📝 Notes

- ⚡ Make sure the Tailwind CSS build process is running while making changes
- 🔄 The output.css file is generated automatically from input.css
- 📱 All layouts are responsive and mobile-friendly 
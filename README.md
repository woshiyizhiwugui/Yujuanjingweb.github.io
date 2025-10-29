# Jing Yujuan - Personal Portfolio Website
A professional personal portfolio showcasing academic background, technical projects, work experience, and achievements. Built with HTML, CSS, and JavaScript, featuring a responsive design and smooth animations.

## Overview
This portfolio website serves as a comprehensive digital resume for Jing Yujuan, a Computer Science student specializing in Embedded Systems, Unity 3D, and Data Analysis. The site presents a clean, modern interface with intuitive navigation across five core sections, highlighting key skills, project details, and professional experiences.

## Features
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scroll animations, hover effects, and expandable project details
- **Organized Structure**: Clear navigation between Home, About, Projects, Experience, and Awards sections
- **Visual Hierarchy**: Consistent color scheme and typography for enhanced readability
- **Performance Optimized**: Lightweight code with efficient asset loading

## Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Libraries/Tools**: Font Awesome (icons), Figma (design reference)
- **Version Control**: Git/GitHub (for deployment and source control)

## File Structure
```
portfolio-website/
├── Home.html          # Landing page with quick navigation
├── About.html         # Academic background & skills
├── Projects.html      # Technical project showcase
├── Experience.html    # Internship & campus experience
├── Awards.html        # Competition achievements & certifications
├── style.css          # Global styling (responsive + animations)
├── images/            # Image assets folder
│   ├── profile.jpg    # Profile picture
│   ├── servo-system.jpg
│   ├── german-board.jpg
│   └── german-website.jpg
└── README.md          # Project documentation
```

## Setup Instructions
1. **Clone the Repository**  
   ```bash
   git clone <repository-url>
   cd portfolio-website
   ```

2. **Prepare Image Assets**  
   - Place your profile picture in the `images/` folder named `profile.jpg`
   - Add project images to the `images/` folder (match filenames in HTML or update references)
   - Recommended image resolutions:
     - Profile: 400×400px (square)
     - Projects: 800×450px (16:9 aspect ratio)

3. **Customize Content**  
   - Update personal details (contact info, education, skills) in respective HTML files
   - Modify project descriptions, experience entries, and award information
   - Adjust color scheme or typography in `style.css` (edit `:root` variables)

4. **Launch the Website**  
   - Open any HTML file in a web browser to preview locally
   - For deployment, host the files on platforms like GitHub Pages, Netlify, or Vercel

## Customization Tips
- To change the primary color: Update `--primary` in the `:root` section of `style.css`
- To modify animations: Adjust values in the `@keyframes` definitions
- To add new sections: Duplicate existing HTML structure and update navigation links
- To change fonts: Replace the `font-family` property in the `*` selector

## Deployment
For free hosting with GitHub Pages:
1. Push the repository to your GitHub account
2. Go to Repository Settings → Pages
3. Select "Main" branch and "root" folder
4. Click "Save" – your site will be live at `https://<username>.github.io/<repository-name>`

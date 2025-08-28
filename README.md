# Linxi Wu - Personal Website

This is a personal website for Linxi Wu, showcasing education, skills, experience, and projects. The website is built with HTML, CSS, and JavaScript, featuring a responsive design with UNC color scheme.

## Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── assets/             # Directory for images and documents
    ├── profile.jpg     # Your profile photo (to be added by you)
    ├── unc-logo.png    # UNC logo (to be added by you)
    ├── resume.pdf      # Your resume (to be added by you)
    └── transcript.pdf  # Your transcript (to be added by you)
```

## How to Modify Content

### Updating Profile Photo

To add your profile photo:

1. Place your photo in the `assets` directory and name it `profile.jpg`
2. In `index.html`, uncomment the line:
   ```html
   <!-- <img id="profile-img" src="assets/profile.jpg" alt="Linxi Wu"> -->
   ```
   And comment out the placeholder line:
   ```html
   <img id="profile-img" src="assets/profile-placeholder.jpg" alt="Linxi Wu">
   ```

### Adding Resume and Transcript

1. Place your resume and transcript PDFs in the `assets` directory
2. Name them `resume.pdf` and `transcript.pdf` respectively

### Updating Content

To modify any text content, simply edit the corresponding sections in `index.html`.

## Deployment Instructions

### Option 1: GitHub Pages

1. Create a GitHub repository
2. Push your website files to the repository
3. Go to repository Settings > Pages
4. Select the branch to deploy (usually `main`)
5. Your site will be published at `https://yourusername.github.io/repository-name/`

### Option 2: Netlify

1. Sign up for a Netlify account
2. Click "New site from Git"
3. Connect to your GitHub repository
4. Select the repository containing your website
5. Click "Deploy site"

### Option 3: Vercel

1. Sign up for a Vercel account
2. Click "New Project"
3. Import your repository from GitHub
4. Configure project settings if needed
5. Click "Deploy"

## Customization

The website uses UNC colors by default:
- Primary color (Carolina Blue): #4B9CD3
- Secondary color (Navy): #13294B

To change the color scheme, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #4B9CD3; /* UNC Carolina Blue */
    --secondary-color: #13294B; /* UNC Navy */
    /* other variables */
}
```
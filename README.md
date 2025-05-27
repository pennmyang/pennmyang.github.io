# My Personal Website

This is the repository for my personal GitHub Pages website.

## Setup Instructions

1. First, make sure you have Git installed on your computer:
   - For macOS: Install via Homebrew with `brew install git`
   - Or download from: https://git-scm.com/downloads

2. Configure Git with your credentials:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

3. Create a new repository on GitHub:
   - Go to https://github.com/new
   - Name it exactly as: `<your-github-username>.github.io`
   - Make it public
   - Don't initialize it with any files

4. Initialize the local repository and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```

5. Your website will be available at: `https://<your-github-username>.github.io`

## Customization

1. Edit the `index.html` file:
   - Replace `[Your Name]` with your actual name
   - Update the "About Me" section with your information
   - Add your interests
   - Update the social links with your actual profiles

2. The `styles.css` file contains all the styling. Feel free to modify colors, fonts, and layout to match your preferences.

## Local Development

To view the website locally, simply open the `index.html` file in your web browser.

## Updates

To update your website, make changes to the files locally, then:
```bash
git add .
git commit -m "Description of your changes"
git push
``` 
# Deploying to GitHub Pages

Follow these steps to deploy the Ventilator Assistant to GitHub Pages:

## 1. Create a New GitHub Repository

1. Go to [GitHub](https://github.com/) and sign in to your account
2. Click the "+" icon in the top-right corner and select "New repository"
3. Name your repository (e.g., "ventilator-assistant")
4. Add a description (optional)
5. Choose whether the repository should be public or private
6. Do NOT initialize with a README, .gitignore, or license (we've already created these)
7. Click "Create repository"

## 2. Push Your Local Repository to GitHub

Run the following commands in your terminal, replacing `yourusername` with your GitHub username:

```bash
# Add the remote repository
git remote add origin https://github.com/yourusername/ventilator-assistant.git

# Push the code to GitHub
git push -u origin main
```

## 3. Configure GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for GitHub to build and deploy your site
7. Your site will be available at: `https://yourusername.github.io/ventilator-assistant/`

## 4. Update README with Correct Demo Link

After your site is deployed, update the demo link in your README.md file:

1. Edit README.md in your repository
2. Replace the placeholder URL with your actual GitHub Pages URL
3. Commit the changes

## 5. Add a Screenshot

1. Visit your deployed application
2. Take a screenshot of the main interface
3. Save it as "screenshot.png"
4. Upload it to your repository
5. The image will automatically appear in your README.md

## Troubleshooting

- If your site doesn't appear, make sure the .nojekyll file is present in your repository
- Check for any build errors in the "Actions" tab of your repository
- Ensure index.html is in the root directory of your repository 
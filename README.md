# 2025

## Step 1: Build the updated site
### Run this from the root of your project
npm run build

## Step 2: Deploy the new build to GitHub Pages
### Navigate into the built site directory
cd dist

### Stage all changes
git add .

### Commit the update
git commit -m "update: refresh site content"

### Push to the GitHub Pages branch (force overwrite)
git push origin gh-pages --force


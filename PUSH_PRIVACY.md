# Push Privacy Policy to GitHub

## Run these commands:

```bash
cd /mnt/c/Users/mohit/OneDrive/Desktop/mlcards_site

# Configure git (only needed once - replace with YOUR info)
git config --global user.email "your-email@example.com"
git config --global user.name "Your Name"

# Commit and push privacy policy
git add privacy.html
git commit -m "Update privacy policy with comprehensive details for Play Store submission"
git push
```

## After pushing:

1. Wait 1-2 minutes for your hosting to deploy (GitHub Pages, Vercel, Netlify, etc.)
2. Your privacy policy will be live at: **https://mlcards.co/privacy.html**
3. Use this URL in Google Play Console!

## If you get authentication error:

You might need to authenticate with GitHub. Follow the prompts to:
- Enter your GitHub username
- Enter your Personal Access Token (not password)

To create a token:
1. Go to: https://github.com/settings/tokens
2. Generate new token (classic)
3. Select scopes: `repo` (full control)
4. Copy the token and use it as password

## Verify it worked:

After deployment, visit: https://mlcards.co/privacy.html

You should see the beautiful purple-themed privacy policy!

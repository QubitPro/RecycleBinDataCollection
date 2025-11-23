# Quick Start Guide

## 🚀 Deploy in 5 Minutes

### 1. Get Your GitHub Token
```
1. Go to: https://github.com/settings/tokens
2. Click "Generate new token (classic)"
3. Select scope: ✅ repo
4. Copy the token
```

### 2. Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### 3. Deploy on Vercel
```
1. Visit: https://vercel.com
2. Click "Add New" → "Project"
3. Import your GitHub repo
4. Add Environment Variables:
   - GITHUB_TOKEN = your_token_here
   - GITHUB_REPO = username/repository
   - FOLDER_PATH = Dataset
5. Click "Deploy"
```

### 4. Test Your App
```
1. Visit your Vercel URL
2. Select a category
3. Start camera
4. Capture and upload a photo
5. Check your GitHub repo for the uploaded image
```

## ⚠️ Important Notes

- Keep your GitHub token secret
- Never commit `.env` files
- Regularly rotate your tokens
- Monitor your repository for uploads

## 🆘 Quick Troubleshooting

| Problem | Solution |
|---------|----------|
| "Failed to fetch configuration" | Add environment variables in Vercel settings |
| "Upload failed" | Check GitHub token permissions (needs `repo` scope) |
| Camera not working | Grant camera permissions & use HTTPS |
| Wrong repository | Verify `GITHUB_REPO` format: `username/repository` |

## 📞 Need Help?

Check the full README.md for detailed instructions and troubleshooting.

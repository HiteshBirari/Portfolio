# 🚀 How to Deploy Your Portfolio to Netlify

## Method 1: Drag and Drop (Easiest)

1. **Create a Netlify Account**
   - Go to [netlify.com](https://www.netlify.com/)
   - Sign up for free using GitHub, GitLab, Bitbucket, or Email

2. **Prepare Your Files**
   - Make sure all your files are in one folder:
     - index.html
     - cover_letter.html
     - style.css
     - script.js
     - assets/resume.pdf

3. **Deploy**
   - Log in to Netlify
   - Go to the "Sites" page
   - Drag and drop your entire project folder onto the deployment area
   - Wait for deployment to complete (usually takes 30 seconds)
   - Your site is live! 🎉

4. **Get Your URL**
   - Netlify will give you a random URL like: `random-name-123456.netlify.app`
   - You can customize this in Site Settings > Domain Management > Options > Change Site Name

---

## Method 2: Using Git (Recommended for Updates)

1. **Initialize Git Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   ```

2. **Push to GitHub**
   - Create a new repository on GitHub
   - Follow GitHub's instructions to push your code:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

3. **Connect to Netlify**
   - Log in to Netlify
   - Click "Add new site" > "Import an existing project"
   - Choose "GitHub" and authorize Netlify
   - Select your repository
   - Click "Deploy site"

4. **Automatic Deployments**
   - Every time you push changes to GitHub, Netlify will automatically redeploy your site!

---

## Method 3: Using Netlify CLI

1. **Install Netlify CLI**
   ```bash
   npm install -g netlify-cli
   ```

2. **Login to Netlify**
   ```bash
   netlify login
   ```

3. **Deploy**
   ```bash
   netlify deploy
   ```
   - Follow the prompts
   - For production deployment:
   ```bash
   netlify deploy --prod
   ```

---

## 🎨 Customizing Your Site

### Change Site Name
1. Go to Site Settings
2. Click "Domain Management"
3. Under "Custom domains", click "Options" > "Edit site name"
4. Enter your desired name: `your-name.netlify.app`

### Add Custom Domain (Optional)
1. Buy a domain from any registrar (GoDaddy, Namecheap, etc.)
2. In Netlify: Site Settings > Domain Management > Add custom domain
3. Follow the instructions to update your DNS settings

---

## 📝 Important Notes

- **Free Plan**: Netlify's free plan is perfect for portfolios
- **HTTPS**: Automatically enabled for all sites
- **Updates**: Just drag and drop again or push to Git to update
- **Build Time**: Usually deploys in under a minute

---

## 🔧 Troubleshooting

**Issue**: Resume PDF not loading
- **Solution**: Make sure the `assets` folder is included when deploying

**Issue**: Links not working
- **Solution**: Check that all file paths are relative (no leading `/`)

**Issue**: Site not updating
- **Solution**: Clear your browser cache or use incognito mode

---

## 📱 Testing Your Site

After deployment, test:
- ✅ All navigation links work
- ✅ Resume downloads correctly
- ✅ Cover letter page loads
- ✅ Mobile responsiveness (resize browser)
- ✅ All social media links work

---

## 🎉 You're Done!

Share your portfolio URL:
- Add it to your resume
- Share on LinkedIn
- Add to your GitHub profile
- Include in job applications

Good luck with your job search! 🚀

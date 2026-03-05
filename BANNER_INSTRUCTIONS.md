# 📸 How to Create Your GitHub Banner

## Method 1: Screenshot from banner.html (Recommended)

1. **Open banner.html**
   - Double-click `banner.html` in your project folder
   - It will open in your browser

2. **Take a Screenshot**
   
   **Option A: Using Browser DevTools (Best Quality)**
   - Press `F12` to open DevTools
   - Press `Ctrl+Shift+P` (Windows) or `Cmd+Shift+P` (Mac)
   - Type "Capture node screenshot"
   - Click on the banner element
   - Save as `banner.png`

   **Option B: Using Snipping Tool**
   - Windows: Press `Win+Shift+S`
   - Mac: Press `Cmd+Shift+4`
   - Select the banner area
   - Save as `banner.png`

3. **Save the Image**
   - Save it as `banner.png` in your portfolio folder
   - Make sure it's in the same folder as README.md

4. **Push to GitHub**
   ```bash
   git add banner.png
   git commit -m "Add portfolio banner"
   git push
   ```

---

## Method 2: Use Online Banner Maker (Alternative)

If you want to create a custom banner online:

### Option 1: Canva
1. Go to [Canva.com](https://www.canva.com/)
2. Create design → Custom size: 1200 x 400 px
3. Use template or create from scratch
4. Add text: "Hi 👋, I'm Hitesh Birari"
5. Add subtitle: "Flutter Developer"
6. Download as PNG
7. Save as `banner.png`

### Option 2: Figma
1. Go to [Figma.com](https://www.figma.com/)
2. Create new file
3. Frame size: 1200 x 400 px
4. Design your banner
5. Export as PNG

### Option 3: GitHub Profile Header Generator
1. Visit: [https://leviarista.github.io/github-profile-header-generator/](https://leviarista.github.io/github-profile-header-generator/)
2. Customize your banner
3. Download and save as `banner.png`

---

## Method 3: Use a Pre-made Template

You can also use these free banner generators:

- [Readme Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)
- [Profile Header Generator](https://leviarista.github.io/github-profile-header-generator/)
- [Banner Maker](https://banner.godori.dev/)

---

## Banner Specifications

- **Recommended Size:** 1200 x 400 pixels
- **Format:** PNG or JPG
- **File Size:** Keep under 1MB for faster loading
- **Colors:** Match your portfolio theme (purple gradient)

---

## Quick Tips

✅ Use high contrast text for readability
✅ Keep it simple and professional
✅ Include your name and title
✅ Match your portfolio color scheme
✅ Test on both light and dark GitHub themes

---

## Troubleshooting

**Banner not showing in README?**
- Make sure `banner.png` is in the same folder as `README.md`
- Check the file name is exactly `banner.png` (case-sensitive)
- Ensure the image is pushed to GitHub
- Wait a few seconds for GitHub to cache the image

**Banner looks blurry?**
- Use at least 1200 x 400 px resolution
- Export as PNG for better quality
- Avoid scaling up small images

---

## Alternative: Use GitHub's Built-in Banner

If you don't want to create a custom banner, you can use dynamic GitHub banners:

```markdown
![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=300&section=header&text=Hitesh%20Birari&fontSize=90&animation=fadeIn&fontAlignY=38&desc=Flutter%20Developer&descAlignY=51&descAlign=50)
```

Just replace the text in your README.md!

---

Good luck with your banner! 🎨

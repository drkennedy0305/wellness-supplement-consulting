# Supplement Consulting Services Website

Professional website for Peg Kennedy's supplement consulting practice, designed to be hosted on GitHub Pages.

## 🌐 What This Is

A professional, mobile-responsive website that showcases your supplement consulting services to primary care practices. The site includes:

- Service descriptions and pricing
- Benefits of partnering with you
- Downloadable marketing materials
- Contact information
- Professional design matching your brand colors

## 📁 What's Included

```
wellness-supplement-consulting/
├── index.html                              # Main website file
├── downloads/                              # Public marketing materials
│   ├── Introduction-Flyer.docx
│   └── Services-Overview.docx
└── README.md                               # This file
```

**Note:** Your internal documents (Email Template, Patient Intake Form, Provider Report Template) are kept separate and NOT uploaded to the public website. These remain private for your use only.

## 🚀 How to Deploy to GitHub Pages (Step-by-Step)

### Option 1: Using GitHub Web Interface (Easiest)

1. **Create a GitHub Account** (if you don't have one)
   - Go to https://github.com
   - Click "Sign up"
   - Follow the prompts

2. **Create a New Repository**
   - Once logged in, click the "+" icon in the top right
   - Select "New repository"
   - Name it: `wellness-supplement-consulting` (or any name you prefer)
   - Make it **Public**
   - ✅ Check "Add a README file"
   - Click "Create repository"

3. **Upload Your Files**
   - In your new repository, click "Add file" → "Upload files"
   - Drag and drop ALL files from the `wellness-supplement-consulting` folder
   - This includes:
     - index.html
     - The entire `downloads` folder with all documents inside
   - Write a commit message: "Initial website upload"
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - In your repository, click "Settings" (top menu)
   - Scroll down to find "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Under "Branch", select "main" and "/ (root)"
   - Click "Save"

5. **Get Your Website URL**
   - Wait 1-2 minutes for deployment
   - Your site will be live at: `https://[your-username].github.io/wellness-supplement-consulting/`
   - GitHub will show you the exact URL in the Pages settings

### Option 2: Using GitHub Desktop (Alternative)

1. Download GitHub Desktop from https://desktop.github.com
2. Install and sign in to your GitHub account
3. Click "Create a New Repository"
4. Name it `wellness-supplement-consulting`
5. Choose where to save it locally
6. Copy all your website files into that folder
7. Commit changes and push to GitHub
8. Follow steps 4-5 from Option 1 to enable Pages

## ✏️ How to Update Your Website

### Updating Content

To change text on your website:
1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the pencil icon (Edit this file)
4. Make your changes
5. Click "Commit changes"
6. Your site will update in 1-2 minutes

### Adding/Updating Documents

To add or replace documents:
1. Go to the `downloads` folder in your repository
2. Click "Add file" → "Upload files"
3. Upload your new/updated documents
4. Commit changes

## 📧 Sharing Your Website

Once your site is live, you can share it by:
- **Email signature**: Add the link to your email signature
- **Business cards**: Include the URL
- **LinkedIn**: Add to your profile or posts
- **Direct sharing**: Send the link to practices you're targeting

Example: "Visit my website at https://[your-username].github.io/wellness-supplement-consulting/"

## 🎨 Customization Tips

### Changing Colors

To change the blue/teal color scheme:
1. Edit `index.html`
2. Find `#2C5F7D` (the main blue color)
3. Replace with your preferred color code (use a color picker online)

### Adding Your Photo

1. Add a photo file to your repository (e.g., `headshot.jpg`)
2. Edit `index.html` 
3. Add this code in the `<header>` section:
```html
<img src="headshot.jpg" alt="Peg Kennedy" style="width: 150px; height: 150px; border-radius: 50%; margin-bottom: 1rem;">
```

### Adding More Content

You can add new sections by copying and pasting the existing section structure in the HTML.

## 🔒 Privacy & Security

- GitHub Pages is secure (HTTPS enabled automatically)
- Documents are publicly accessible (by design)
- Don't upload any files with patient information
- Don't include personal information you want kept private

## 💡 Pro Tips

1. **Custom Domain**: You can use your own domain name (e.g., www.pegkennedywellness.com) by:
   - Purchasing a domain from Namecheap, GoDaddy, etc.
   - Following GitHub's custom domain setup instructions

2. **Analytics**: Add Google Analytics to track visits:
   - Create a Google Analytics account
   - Add the tracking code to your `index.html` file

3. **SEO**: To help practices find you via Google:
   - Add keywords to your page titles
   - Create a Google Business Profile
   - Share your link on professional networks

## 📱 Mobile Friendly

The website is fully responsive and looks great on:
- Desktop computers
- Tablets
- Smartphones

## ❓ Troubleshooting

**Problem**: Website isn't loading
- **Solution**: Wait 2-3 minutes after enabling Pages, then clear your browser cache

**Problem**: Downloads aren't working
- **Solution**: Make sure the `downloads` folder uploaded correctly with all files inside

**Problem**: Changes aren't showing
- **Solution**: Clear your browser cache (Ctrl+Shift+Delete on Windows, Cmd+Shift+Delete on Mac)

## 📞 Need Help?

If you run into issues:
1. Check GitHub's documentation: https://docs.github.com/pages
2. Google the specific error message
3. GitHub has excellent community forums for help

## 🎯 Next Steps After Deployment

1. ✅ Test all download links to make sure documents download correctly
2. ✅ View the site on your phone to ensure it looks good
3. ✅ Share the link with a colleague for feedback
4. ✅ Add the URL to your email signature
5. ✅ Include it in your LinkedIn profile
6. ✅ Start sharing with practices!

---

**Website URL Format**: `https://[your-github-username].github.io/wellness-supplement-consulting/`

Replace `[your-github-username]` with your actual GitHub username.

Example: If your GitHub username is "pkennedy" your site would be:
`https://pkennedy.github.io/wellness-supplement-consulting/`

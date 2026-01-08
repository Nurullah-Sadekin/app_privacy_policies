# App Privacy Policies

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://nurullah-sadekin.github.io/app_privacy_policies/)

A centralized privacy policy hub for all applications developed by Nurullah Sadekin.

## 🔗 Live Privacy Policies

**Main Hub:** https://nurullah-sadekin.github.io/app_privacy_policies/

### Individual Privacy Policies

- **Video Converter:** https://nurullah-sadekin.github.io/app_privacy_policies/converter-privacy.html
- **Countdown Timer:** https://nurullah-sadekin.github.io/app_privacy_policies/countdown-privacy.html

## 📱 Applications Covered

### 1. Video Converter
A simple and powerful video conversion tool that processes everything locally on your device.
- **Repository:** https://github.com/Nurullah-Sadekin/converter
- **Privacy Commitment:** Zero data collection, all processing local

### 2. Countdown Timer
A beautiful countdown timer application with full privacy protection and local data storage.
- **Repository:** https://github.com/Nurullah-Sadekin/countdown
- **Privacy Commitment:** No tracking, all data stored locally

## 🔒 Privacy Commitment

All applications featured here:
- ✅ Don't collect personal data
- ✅ Process everything locally
- ✅ Work completely offline
- ✅ Are open source and verifiable
- ✅ Don't use analytics or tracking
- ✅ Are safe for all ages

## 🚀 Setup GitHub Pages

This repository is configured to automatically deploy to GitHub Pages.

### Enable GitHub Pages

1. Go to repository **Settings** → **Pages**
2. Under **Source**, select:
   - **Source:** GitHub Actions
3. The site will be automatically deployed on every push to `main`/`master`

### Manual Deployment

You can also trigger a manual deployment:
1. Go to **Actions** tab
2. Select **Deploy to GitHub Pages** workflow
3. Click **Run workflow**

## 📁 Repository Structure

```
app_privacy_policies/
├── index.html                    # Main privacy policy hub
├── converter-privacy.html        # Video Converter privacy policy
├── countdown-privacy.html        # Countdown Timer privacy policy
├── .github/
│   └── workflows/
│       └── pages.yml            # GitHub Pages deployment workflow
└── README.md                     # This file
```

## 🛠️ Local Development

To preview the privacy policies locally:

```bash
# Option 1: Using Python
python3 -m http.server 8080

# Option 2: Using Node.js
npx http-server -p 8080

# Option 3: Using PHP
php -S localhost:8080
```

Then visit: http://localhost:8080

## 📝 Adding New Privacy Policies

To add a new application privacy policy:

1. Create a new HTML file (e.g., `newapp-privacy.html`)
2. Update `index.html` to include a link to the new policy
3. Commit and push changes
4. GitHub Actions will automatically deploy

## 📧 Contact

For questions or concerns about privacy policies:
- Open an issue in the respective application repository
- Contact via GitHub discussions

## 📄 License

The privacy policy content and structure are provided for transparency.

---

**Last Updated:** January 8, 2026

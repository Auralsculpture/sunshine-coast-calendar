# Sunshine Coast Bahá'í Community Calendar

Automated event calendar system with form submissions and automatic calendar generation.

## 🌟 Features

- Beautiful HTML form with interactive date picker (supports multiple dates and ranges)
- Automatic submission to Google Sheets
- One-click calendar regeneration
- Automatic push to GitHub Pages
- Mobile responsive
- Embeddable in Google Sites

## 📁 Files

- **event-form.html** - Event submission form with date picker
- **calendar.html** - Generated calendar display (auto-updated by Apps Script)
- **apps-script-backend.js** - Google Apps Script code (in local project folder)
- **SETUP_INSTRUCTIONS.md** - Complete setup guide (in local project folder)

## 🚀 Quick Start

### GitHub Setup (Already Complete! ✅)
- Repository created
- Files uploaded
- Ready for GitHub Pages

### Remaining Steps:

1. **Enable GitHub Pages** (2 minutes)
   - Settings → Pages → Deploy from branch: main

2. **Create Personal Access Token** (3 minutes)
   - Settings → Developer settings → Personal access tokens
   - Generate new token (classic) with `repo` scope

3. **Set up Google Sheets** (10 minutes)
   - Create spreadsheet
   - Add Apps Script code
   - Deploy as web app
   - Update form with script URL

4. **Test the system** (5 minutes)

## 🔗 URLs (After Enabling Pages)

- **Form**: https://auralsculpture.github.io/sunshine-coast-calendar/event-form.html
- **Calendar**: https://auralsculpture.github.io/sunshine-coast-calendar/calendar.html

## 📖 Full Documentation

See `SETUP_INSTRUCTIONS.md` in your local project folder for complete step-by-step instructions.

## 🎯 Workflow

**For Community Members:**
1. Fill form → Auto-submitted to Google Sheets

**For Admin:**
1. Check submissions in spreadsheet
2. Click "Calendar Tools" → "Regenerate Calendar"
3. Calendar auto-updates on website in 30 seconds

## 🔧 Customization

- Change colors: Search for `#673ab7` in HTML files
- Change date range: Modify dates in Apps Script
- Add branding: Add image to form header

## 📅 Date Range

Initial calendar displays: November 2025 - February 2026  
Form accepts: Any future date

---

**Status**: Repository configured ✅ | Awaiting Google Sheets setup
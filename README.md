# 🎯 Demo Tracker - SDR Sales Pipeline Manager

A standalone HTML tool for Sales Development Representatives to track and manage demo calls. No installation, no server, no database required - just open and use!

**[🚀 Use It Now](https://zpcolburn.github.io/demo-tracker/)** | **[📥 Download](https://github.com/zpcolburn/demo-tracker/archive/refs/heads/main.zip)**

---

## ✨ Features

### 📊 Demo Management
- Track contact info (name, firm, email)
- Schedule demo dates and times
- Link to Salesforce records
- Status tracking (Scheduled, Completed, No Show, Rescheduled)
- Account creation tracking with conversion rate stats

### ✅ Task Management
- **Auto-generate check-in tasks** 3 working days before demos
- Custom task creation for any demo
- Edit task names, dates, and times
- **Google Calendar integration** - one-click to add tasks
- Automatic weekend skipping (respects working days)

### 📝 Notes & Organization
- Add notes to individual demos
- General notes with optional demo linking
- Working days configuration
- Filter demos by status
- Email integration (Gmail quick links)

### 💾 Data Protection
- **Export backups** anytime (downloadable JSON file)
- **Import backups** to restore data
- **Auto-save every 12 hours** to browser storage
- All data stored locally - 100% private

---

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
1. Visit **[https://zpcolburn.github.io/demo-tracker/](https://zpcolburn.github.io/demo-tracker/)**
2. Bookmark the page
3. Start adding demos!

### Option 2: Download and Use Locally
1. Download `index.html` from this repository
2. Double-click the file to open in your browser
3. Bookmark the file location for easy access

---

## 📖 How to Use

### Adding a Demo
1. Fill in the form at the top:
   - First Name, Last Name, Firm Name
   - Email (optional - for Gmail integration)
   - Demo Date and Time
   - Status
   - Salesforce Link (optional)
2. Click **"➕ Add Demo"**
3. Demo appears in the table below

### Managing Tasks
**Auto-Generated Tasks:**
- System automatically creates check-in tasks 3 working days before demos
- Tasks appear in "Upcoming Tasks" section

**Manual Tasks:**
- Click **"▼ Details"** on any demo
- Click **"➕ Create Task"**
- Choose date, time, and description
- Click **"Create Task"**

**Editing Tasks:**
- Click **"✏️ Edit"** on any task
- Change description, date, or time
- Click **"Create Task"** to save

**Add to Google Calendar:**
- Click **"📅 Add to Calendar"** on any task
- Google Calendar opens with pre-filled event
- Click **"Save"** in Google Calendar

### Tracking Progress
- Check **"Account Created"** when prospect signs up
- Conversion rate auto-calculates
- Filter demos by status using dropdown

### Taking Notes
**Demo-Specific Notes:**
1. Click **"▼ Details"** on a demo
2. Type note in text box
3. Click **"Add Note"** or press Enter

**General Notes:**
1. Use the General Notes section (right side)
2. Optionally link to a specific demo
3. Click **"Add Note"**

---

## 💾 Backing Up Your Data

### Export Backup (Recommended Weekly)
1. Click **"📤 Export Backup"** at the top
2. File downloads: `demo-tracker-backup-YYYY-MM-DD.json`
3. Save this file somewhere safe:
   - Desktop folder
   - Google Drive / Dropbox
   - External drive

### Import Backup
1. Click **"📥 Import Backup"**
2. Select your backup `.json` file
3. All data restores instantly

### Auto-Save
- Automatically saves to browser storage every 12 hours
- Status shows last save time
- **Note:** Auto-save is browser-specific (see below)

---

## ⚠️ Important: Data Storage

### How Data is Stored
- All data is stored in your **browser's localStorage**
- Data is **private** - stays on your device only
- Works offline - no internet required after first load

### Data Persistence
✅ **Data WILL persist:**
- Normal browser use
- Browser updates
- Computer restarts
- Closing and reopening browser

❌ **Data MAY be lost if you:**
- Clear browser history/cache/cookies
- Use Incognito/Private mode
- Switch browsers (Chrome → Firefox)
- Switch devices (laptop → desktop)
- Uninstall/reinstall browser

### 🛡️ Protection Strategy
**To keep your data safe:**
1. **Export backups weekly** (click 📤 Export Backup)
2. Save backup files to cloud storage (Google Drive/Dropbox)
3. Before clearing browser data, export a backup
4. When switching devices, export → import on new device

---

## 🔧 Working Days Configuration

Configure which days you work:
1. Check/uncheck days at the top (Mon-Sun)
2. Auto-tasks skip non-working days
3. Tasks automatically adjust to working days

**Example:** Demo on Monday → Check-in task scheduled for Friday (3 working days before)

---

## 💡 Tips & Best Practices

### For Best Results:
- **Export backups regularly** - set a weekly reminder
- Keep backup files in cloud storage for easy access
- Use **Chrome or Edge** for best compatibility
- **Bookmark the page** for quick access
- Link Salesforce records for easy reference

### Task Management:
- Edit task names to be specific (e.g., "Send pricing deck")
- Add to Google Calendar to get reminders
- Mark tasks complete when done (✓ Complete button)

### Gmail Integration:
- Add email addresses to open Gmail conversations
- Quickly reference past discussions

---

## 🔒 Privacy & Security

- **100% client-side** - no data sent to servers
- **No tracking** - no analytics or cookies
- **No accounts** - no login required
- **Open source** - view all code in index.html
- Data never leaves your device (except your backups)

---

## 🌐 Browser Compatibility

Works on all modern browsers:
- ✅ Chrome (recommended)
- ✅ Edge
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (Chrome Mobile, Safari Mobile)

---

## 📱 Mobile Use

The tracker works on mobile devices:
- Full functionality on phone/tablet
- Responsive design
- Touch-friendly interface
- Save to home screen for app-like experience

---

## 🤝 Sharing with Team

### Each person gets their own tracker:
1. Share the GitHub Pages link: `https://zpcolburn.github.io/demo-tracker/`
2. Each person's data is separate and private
3. Everyone manages their own pipeline

**Note:** This is designed for individual use. For team-wide collaboration where everyone sees the same demos, a database solution would be needed.

---

## 🆘 Troubleshooting

### Lost Your Data?
1. Check if you're in the same browser you used before
2. Make sure you're not in Incognito/Private mode
3. Import your most recent backup file

### Tasks Not Generating?
- Make sure demo is more than 14 days away
- Check your working days configuration
- Refresh the page

### Calendar Button Not Working?
- Make sure you have Google Calendar account
- Check if pop-ups are blocked
- Try a different browser

---

## 📄 Technical Details

- **File Size:** ~50KB
- **Technology:** Pure HTML, CSS, JavaScript
- **Storage:** Browser localStorage API
- **Dependencies:** None - completely standalone
- **Offline:** Works fully offline after first load

---

## 📧 Support

Questions or issues? Open an issue on GitHub or contact the repository owner.

---

## 📜 License

Free to use for personal and commercial purposes. No attribution required.

---

**Made with ❤️ for SDRs who want a simple, powerful demo tracker without the bloat.**

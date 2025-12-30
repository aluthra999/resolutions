# 2025 Resolution Tracker

A beautiful, mobile-first web app to track your New Year's resolutions with partner accountability features.

## Features ✨

### Core Features
- **Goal Tracking**: Create unlimited resolutions with progress tracking
- **Progress Visualization**: Beautiful progress bars and completion percentages
- **Streak Tracking**: Monitor consecutive days of progress
- **Partner System**: Connect with an accountability partner via unique codes
- **Shared Goals**: Make resolutions visible to your partner for mutual motivation
- **Monthly Reflections**: Document your journey with mood tracking
- **Privacy Controls**: Toggle what partners can see

### Design Highlights
- Mobile-first, fully responsive design
- Dark theme with gold accents and smooth animations
- No external dependencies - works offline after first load
- All data stored locally in your browser (private & secure)

## How to Use 🚀

### Option 1: GitHub Pages (Recommended - 100% Free)

1. Create a GitHub account (if you don't have one)
2. Create a new repository (e.g., "resolution-tracker-2025")
3. Upload `resolution-tracker.html` to the repository
4. Go to Settings → Pages
5. Select "main" branch as source
6. Your site will be live at: `https://yourusername.github.io/resolution-tracker-2025/resolution-tracker.html`

**To use a cleaner URL:**
- Rename the file to `index.html` before uploading
- Your site will be at: `https://yourusername.github.io/resolution-tracker-2025/`

### Option 2: Local Use

Simply double-click the HTML file - it works immediately in any browser!

### Option 3: Other Free Hosting

- **Netlify Drop**: Drag & drop the file at netlify.com/drop
- **Vercel**: Upload via vercel.com (requires GitHub)
- **Cloudflare Pages**: Free hosting with custom domains

## Using the App 📱

### Creating Resolutions
1. Click "Add Resolution"
2. Enter your goal (e.g., "Read 24 books")
3. Set your target number and unit
4. Optionally share with partner

### Tracking Progress
1. Click the 📊 icon on any goal
2. Update your current progress
3. Watch your streak grow!

### Partner Connection
1. Go to "Partner" tab
2. Share your connection code with your partner
3. Enter their code to connect
4. View each other's shared goals

### Monthly Reflections
1. Go to "Reflections" tab
2. Add monthly check-ins
3. Track mood and document your journey

## Privacy & Data 🔒

- **All data stays on your device** - stored in browser localStorage
- No servers, no accounts, no tracking
- Export your data anytime as JSON
- Partner connections are simulated (no real backend sync)

**Note on Partner Feature**: The current version stores everything locally. In a future version with a backend, partners would truly sync data. For now, both partners maintain their own copies.

## Customization 🎨

Want to tweak the design? The HTML file contains everything you need:
- Edit CSS variables at the top of the `<style>` section to change colors
- Modify fonts by changing the Google Fonts import
- Adjust animations by editing `@keyframes` rules

## Data Export & Backup 💾

- Go to Settings → Export Your Data
- Download JSON backup of all your resolutions and reflections
- Import by using browser developer tools to set localStorage

## Browser Compatibility ✅

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari (iOS/macOS)
- Samsung Internet

## Future Enhancement Ideas 💡

Some ideas if you want to extend this:

1. **Real Backend Sync**: Add Firebase or Supabase for true partner syncing
2. **Reminders**: Add browser notifications for daily check-ins
3. **Charts**: Visualize progress over time with Chart.js
4. **Themes**: Add light mode toggle
5. **Import/Export CSV**: For spreadsheet compatibility
6. **Social Sharing**: Share milestones on social media

## Troubleshooting 🔧

**Data not saving?**
- Check if browser allows localStorage
- Try a different browser
- Ensure you're not in incognito/private mode

**Partner connection not working?**
- Remember: connections are local-only in this version
- Both partners need to manually share their own updates
- Consider adding a backend for real-time sync

**Mobile display issues?**
- Refresh the page
- Try landscape mode for better stats view
- Ensure zoom is at 100%

## License

Free to use, modify, and share! 🎉

---

Made with ❤️ for crushing your 2025 goals!

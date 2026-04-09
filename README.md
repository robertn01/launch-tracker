# 🚀 Space Launch Tracker

A real-time web dashboard showing upcoming rocket launches worldwide with live countdown timers.

## 🌐 Live Dashboard

**Access the dashboard:** https://robertn01.github.io/launch-tracker/

## Features

✅ **Real-time Launch Data** - Fetches current information from RocketLaunch.Live API  
✅ **Live Countdown Timer** - Updates every second to show time until next launch  
✅ **Complete Launch Info** - Mission name, rocket type, launch site, and agency  
✅ **Advanced Filtering** - View all, this week, or this month's launches  
✅ **Beautiful UI** - Dark theme with glassmorphism design  
✅ **Fully Responsive** - Optimized for desktop, tablet, and mobile  
✅ **Fallback Data** - Works even if API is temporarily unavailable  

## 📊 Dashboard Sections

### Statistics Bar
- **Upcoming Launches** - Total count of scheduled launches
- **This Month** - Launches scheduled for current calendar month
- **Days to Next** - Days remaining until next launch
- **Space Agencies** - Number of different agencies with launches

### Next Launch Countdown
- Large countdown display (Days : Hours : Minutes : Seconds)
- Mission details (name, rocket, site, agency)
- Real-time updates every second

### Upcoming Launches Grid
- Cards showing next 50 launches
- Each card displays:
  - Launch date/time
  - Mission name
  - Rocket type
  - Operating agency
  - Launch site
  - Mini countdown timer
  - Status badge

## 🚀 Quick Start

Simply visit the live dashboard: https://robertn01.github.io/launch-tracker/

No installation required!

## 📡 Data Source

The dashboard fetches real launch data from the **RocketLaunch.Live API**:
- Free tier, no authentication required
- Updated in real-time
- Covers launches from all major space agencies

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **API**: RocketLaunch.Live (free public API)
- **Hosting**: GitHub Pages
- **Browser Compatibility**: All modern browsers

## 🎨 Design Features

- **Dark Space Theme** - Professional starfield gradient background
- **Glassmorphism** - Modern frosted glass effect with backdrop blur
- **Purple Accent Color** - Primary #667eea with complementary #764ba2
- **Smooth Animations** - Hover effects, spinning loading indicator
- **Responsive Layout** - Works on all screen sizes

## 🔄 Auto-Updates

The countdown timer updates automatically every second for the main display and each launch card.

## 🐛 Error Handling

- **API Failure**: Uses curated fallback dataset of realistic future launches
- **Network Issues**: Graceful error messages displayed to user
- **Empty Results**: Helpful message if no upcoming launches found

---

**Built for space enthusiasts** | **Live on GitHub Pages** | **Real-time data**

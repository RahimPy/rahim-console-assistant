🎮 Console Auto Form Tool
📋 Overview
A powerful web-based automation tool for console testing forms with batch processing capabilities, statistics tracking, and keyboard shortcuts.

✨ Features
🚀 Form Types
FAILED TEST - Detailed cascade logic testing with failure point tracking

REJECTION - Single reason rejection forms

PASS ALL TESTS - Auto-marks tests as "Passed" or "Not testable"

⚡ Batch Processing
Queue multiple forms for offline work

Open ALL queued forms with one click (1-second delays between each)

Auto-fills ALL fields including general field

Handles special consoles correctly (PS5 Digital, Xbox Series S, etc.)

📊 Statistics Dashboard
Real-time tracking of forms processed

Console-specific statistics (PlayStation, Xbox, Nintendo, Handheld PCs)

Today vs All-time views

Category breakdowns

⌨️ Keyboard Shortcuts
Ctrl + Enter - Open current form

Ctrl + Q - Add to queue

Ctrl + 1/2/3 - Switch form types

Ctrl + L - Open sidebar dashboard

F2 - Swap ID/Serial fields

Esc - Close sidebar

🛠️ Special Console Handling
The tool automatically marks tests as "Not testable" for consoles where certain tests don't apply:

Console	Not Testable Tests
PlayStation 5 Digital	Battery, Display, Speaker/Mic, Disc Storage
Xbox Series S	Battery, Display, Speaker/Mic, Disc Storage
PlayStation Portable	Controller
Nintendo DS	Network, Accounts, Controller
And many more...	
🎨 Design Features
Responsive layout - Works on desktop and mobile

Dark theme with gradient backgrounds

Multi-color animated name in footer

Clean, modern interface with glass-morphism effects

Visual feedback for all interactions

📁 File Structure
text
console-auto-form/
├── index.html          # Main application file
├── README.md           # This documentation
└── (Optional assets)
🚀 Quick Start
Open index.html in any modern web browser

Select form type (Failed Test, Rejection, or Pass All Tests)

Fill required fields (Item ID, Serial Number, etc.)

Use buttons or keyboard shortcuts:

Open Form Now - Immediately opens filled form

Add to Queue - Stores form for batch processing

Clear Form - Resets all fields

📈 Queue Management
Adding to Queue
Fill out any form type

Click "Add to Queue" or press Ctrl + Q

Forms are saved in browser's localStorage

Batch Processing
Click hamburger menu ☰ to open sidebar

View all queued forms

Click "Open All Forms" to process entire queue

Forms open sequentially with 1-second delays

Export Options
CSV Export - Download queue as spreadsheet

Statistics Export - View in dashboard

🔧 Technical Details
Browser Compatibility
Chrome 80+

Firefox 75+

Safari 13+

Edge 80+

Storage
Uses localStorage for persistent data

Stats reset daily at midnight

Queue persists between browser sessions

Google Forms Integration
Pre-fills forms via URL parameters

Supports all test types and failure reasons

Handles special characters and encoding

⚠️ Important Notes
Google Forms Limitation: Some dropdowns may not auto-select from URL parameters. Always verify form fields after opening.

Browser Pop-up Blockers: Allow pop-ups for this site to enable batch opening.

Data Persistence: Data is stored in your browser only. Clear browser data will reset everything.

🐛 Troubleshooting
Issue	Solution
Forms not opening	Check pop-up blocker settings
Queue not saving	Clear browser cache and reload
Keyboard shortcuts not working	Ensure no other app is using same shortcuts
Stats not updating	Check browser console for errors
📝 Changelog
Latest Updates
✅ Responsive keyboard shortcuts panel

✅ Batch system opens ALL queued forms

✅ Auto-fills general field for all form types

✅ Special console handling fixes

👤 Author
Created by RAHIM

📄 License
This tool is for personal/educational use. Not for commercial distribution.

💡 Tip: Use keyboard shortcuts for maximum efficiency! The tool is designed for rapid form filling with minimal mouse usage.

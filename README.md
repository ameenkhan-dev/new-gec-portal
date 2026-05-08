# GEC Event Portal 

A complete event management portal for GEC with authentication, role-based dashboards, and event approval workflow.

## Features

### 🔐 Authentication
- Login & Registration with role selection
- Email validation (@gec.ac.in only)
- Secure password storage (localStorage)
- Role-based access control

### 👨‍🎓 Student Dashboard
- View all approved events
- Register for events (capacity check)
- View my registrations
- Unregister from events

### 🎯 Club Leader Dashboard
- Draft new events (name, description, date, location, capacity)
- Submit events for approval
- View all my events (pending/approved/rejected)
- See registration count for each event
- Delete events

### ⚙️ Super Admin Dashboard
- Manage all users (view/delete)
- Approve/Reject pending events
- View all approved events with registration stats
- View dashboard metrics

## Event Workflow

1. **Club Leader** drafts an event
2. Event goes to **Pending** status
3. **Super Admin** reviews and approves/rejects
4. **Students** see approved events and register
5. Registration count tracked up to event capacity

## Test Credentials

```
🔑 Admin Account:
Email: admin@gec.ac.in
Password: admin123

🎯 Club Leader:
Email: club@gec.ac.in
Password: club123

👨‍🎓 Student:
Email: student@gec.ac.in
Password: student123
```

## How to Use

1. Open `index.html` in any browser
2. All data stored in browser localStorage (persists)
3. Register new accounts with @gec.ac.in emails
4. Test all 3 roles and workflows

## Deployment

- **Single HTML file** - No build process needed
- Deploy to any static host (Netlify, Vercel, GitHub Pages, etc.)
- Works offline - all data in browser

## Tech Stack

- Pure HTML5
- Vanilla CSS3
- Vanilla JavaScript (ES6+)
- localStorage for data persistence

Made with ❤️ for GEC Event Management

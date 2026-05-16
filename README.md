# 🎯 ACKTIB Sales System
**Complete Sales & Personal Development Management System**

A fully integrated, browser-based platform for sales professionals to manage daily activities, track metrics, reflect on progress, and build professional skills—all without requiring a server.

---

## 📱 Live Dashboard
**Access from anywhere:** https://dccodoceo-creator.github.io/acktib-sales-system/

Works on:
- 💻 Desktop (Mac, Windows, Linux)
- 📱 Mobile (iPhone, Android)
- 📊 Tablet

---

## 🎯 What is ACKTIB?

ACKTIB is a **personal business intelligence system** designed for sales executives who need:
- Daily structure and accountability
- Real-time metrics tracking
- Professional reflection and growth
- Objection handling optimization
- Cross-device accessibility

It complements (not replaces) your CRM like Pipedrive—this is your personal operations center.

---

## 🔧 7 Core Tools

### 1. **🎯 Central Dashboard** (index.html)
Your command center with real-time stats.

**Features:**
- Live clock and current date
- Today's calls, talks, proposals (auto-updated)
- Weekly totals
- Total entries in system
- Quick action buttons (AM Plan, Register Metrics, Journal, Calendar)
- Full tool directory with descriptions
- Weekly workflow timeline
- System status indicators

**When to use:** Every morning as your first stop

---

### 2. **⏰ Daily Notifications & Tasks** (daily_notifications.html)
Automatic morning and evening planning.

**Features:**
- **Plan AM (9:00 AM)**: Define 3 daily priorities + checklist
- **Review PM (5:45 PM)**: Reflect on completion, clients, learnings
- Real-time clock showing next notification
- Daily history view
- Auto-notification toggle
- Client tracking table

**What to log:**
- 3 Daily Priorities
- Daily checklist items
- Calls made / Responses received
- Talks completed
- Proposals submitted
- Client names (with company, objection, result)
- Key learnings

**Goal:** Accountability and daily closure

---

### 3. **📊 Metrics Dashboard** (metrics_dashboard.html)
Weekly, monthly, and personal KPI tracking.

**Features:**
- Weekly metrics (calls, talks, proposals, conversion rates)
- Monthly KPIs and revenue tracking
- Personal skill metrics
- Interactive Chart.js visualizations
- Recent entries list
- Custom metric entry form

**What to track:**
- Daily: Calls, responses (%), talks, proposals, avg call duration
- Weekly: Total calls (goal 50), talks (goal 4), conversion ratio
- Monthly: Total calls (goal 200), revenue, trends
- Personal: Skills rating (1-10 scale)

**Goal:** Data-driven decisions and goal progress

---

### 4. **📝 Journal System** (journal_system.html)
Deep reflection for operational memory and growth.

**Features:**
- **Daily Journal (Mon-Fri)**: Important points, observations, notes
- **Friday Journal**: Weekly review (what went well, challenges, metrics review, next focus)
- **Sunday Journal**: Mental prep, weekly objective, day-by-day planning
- History by journal type
- Full-text entries with timestamps
- Edit and delete capability

**What to write:**
- Daily: Key client interactions, success patterns, objections faced, technical notes
- Friday: Weekly wins, obstacles overcome, team feedback, competitive intel
- Sunday: Mental preparation, week's priority, energy management plan

**Goal:** Build operational wisdom and self-awareness

---

### 5. **📅 Calendar Dashboard** (calendar_dashboard.html)
Monthly activity view with day-by-day editing.

**Features:**
- Full month calendar view
- Click any day to view/edit data
- Modal editor with 3 tabs:
  - **Calls & Talks**: Track calls made, talks completed
  - **Proposals**: Track proposals sent and results
  - **Journal**: Link to daily journal entries
- Navigation between months
- Activity indicators on calendar

**How to use:**
1. Click a date on the calendar
2. Switch between tabs
3. Add calls, talks, proposals, or journal notes
4. Data auto-saves

**Goal:** Visual overview of weekly/monthly activity patterns

---

### 6. **⚠️ Objections Playbook** (playbook_objections.html)
Database of client objections with effective scripts.

**Features:**
- **Database Tab**: View all objections with success rates
- **Add Objection Tab**: Create new objection entries with:
  - Exact objection text
  - Frequency (# of times faced)
  - Effective script / response
  - Success rate (%)
  - Industry/context
  - Variant notes
- **Statistics Tab**:
  - Total objections tracked
  - Average success rate
  - Most common objection
  - Top 3 effective scripts
  - Low-performing scripts to improve

**Best practices:**
- Add objection immediately after call
- Test different scripts and rate effectiveness
- Review "To Improve" section weekly
- Update success rates as you refine responses

**Goal:** Build a personal playbook that improves over time

---

### 7. **👤 Personal Tracker** (personal_tracker.html)
Your professional evolution dashboard.

**Features:**
- **Skills Tab**: Track 1-10 skill ratings over time
  - Communication
  - Negotiation
  - Product knowledge
  - Time management
  - etc.
- **Feedback Tab**: Log feedback from different sources
  - Manager feedback
  - Executive feedback
  - Client feedback
  - Self-assessment
- **Progress Tab**: Month-by-month evolution
- **Summary**: Strengths, areas to improve, next focus

**How to use:**
1. Add skills you're developing
2. Rate yourself monthly (1-10 scale)
3. Log feedback from calls/1-1s/reviews
4. Track trends over 3-6 months
5. Review on Sunday for weekly planning

**Goal:** Visible professional growth and self-awareness

---

## 📅 Recommended Daily Workflow

### **Monday-Friday**

| Time | Action | Tool | Notes |
|------|--------|------|-------|
| **9:00 AM** | Plan AM | Daily Notifications | Define 3 priorities + checklist |
| **Throughout Day** | Execute & Log | Calendar / Metrics | Track calls, talks, proposals |
| **5:45 PM** | Review PM | Daily Notifications | Reflect on day, log learnings |
| **Evening** | Journal (Optional) | Journal System | Deeper reflection |

### **Friday Afternoon**
- Open **Friday Journal**
- Reflect: wins, challenges, metrics vs goals
- Plan next week's focus

### **Sunday**
- Open **Sunday Journal** + **Personal Tracker**
- Mental preparation for week
- Review skill development
- Plan week day-by-day

### **Anytime**
- Update **Objections Playbook** after difficult calls
- Review **Metrics Dashboard** for weekly analysis
- Check **Calendar Dashboard** for visual patterns

---

## 💾 Data Storage & Privacy

**How it works:**
- All data stored in **browser localStorage** (your device only)
- No server, no cloud sync, no privacy concerns
- Data persists between sessions
- Each browser/device has separate localStorage

**Storage breakdown:**
- Daily Notifications: `plan_[date]`, `review_[date]`
- Journal: `journal_daily`, `journal_friday`, `journal_sunday`
- Metrics: `dashboard_metrics`
- Objections: `playbook_objections`
- Personal Tracker: `development_tracker_*`
- Calendar: `dashboard_metrics` (shared)

**Backup & Export:**
- Export via browser DevTools Console if needed
- Or screenshot/document important entries
- Data is safe as long as browser cache isn't cleared

---

## 🚀 Getting Started

### **First Time Setup (5 minutes)**
1. Open **Central Dashboard** (index.html)
2. Read the "Where to Start?" section
3. Open **Daily Notifications** → Complete Plan AM for today
4. Open **Metrics Dashboard** → Add first day's metrics
5. Add 1-2 objections to the **Playbook** from recent calls

### **First Week**
- Complete AM Plan every morning
- Log metrics at end of day
- Complete Review PM at 5:45 PM
- Add journal entries for 2-3 days

### **First Month**
- Complete all daily routines consistently
- Review Metrics Dashboard weekly
- Complete Friday Journal every Friday
- Track 3-4 skills in Personal Tracker
- Build objections database (15+ entries)

---

## 📊 Key Performance Indicators (KPIs)

### **Daily**
- Calls made
- Response rate (responses ÷ calls)
- Talks completed
- Proposals submitted
- Average call duration

### **Weekly**
- Total calls (goal: 50)
- Talks (goal: 4)
- Talk-to-proposal conversion
- Objection handling success rate
- Time on high-value activities

### **Monthly**
- Total calls (goal: 200)
- Talks (goal: 16)
- Revenue generated
- Growth in skill ratings
- Objection success rate improvement

---

## 🔗 Integration with Other Tools

**This system complements (not replaces):**
- **Pipedrive**: Your primary CRM for deals
- **Google Calendar**: For meeting scheduling
- **Slack**: For team communication
- **Email**: For customer correspondence

**Workflow:**
1. Log calls/talks in ACKTIB
2. Transfer key deals to Pipedrive
3. Update objections playbook
4. Reflect in journal
5. Review metrics weekly

---

## 💡 Pro Tips

### **For Maximum Effectiveness:**
1. **Complete AM Plan before opening email** — Sets intention
2. **Log metrics same day** — Data accuracy matters
3. **Review PM at exactly 5:45 PM** — Creates closure ritual
4. **Journal on Friday** — Weekly pattern identification
5. **Update Objections after difficult calls** — While fresh
6. **Review Personal Tracker on Sunday** — Growth mindset prep

### **For Consistency:**
- Pin the dashboard URL to your phone home screen
- Set calendar reminders for AM (9:00) and PM (5:45)
- Review dashboard every Friday
- Share weekly metrics with your manager/mentor

### **For Growth:**
- Identify your 3 weakest objection responses
- Practice those scripts daily
- Re-rate skills monthly (not weekly)
- Track patterns in your journal
- Celebrate wins in Friday Journal

---

## 🛠️ Technical Details

**Built with:**
- Pure HTML5 + CSS3 + Vanilla JavaScript
- Chart.js for visualizations
- localStorage for data persistence
- Responsive design (mobile-first)
- No external dependencies (except Chart.js)

**Browser Support:**
- Chrome/Edge: ✅ Full support
- Safari: ✅ Full support
- Firefox: ✅ Full support
- Mobile browsers: ✅ Full support

**File Sizes:**
- index.html: 23KB
- daily_notifications.html: 23KB
- journal_system.html: 21KB
- metrics_dashboard.html: 25KB
- playbook_objections.html: 15KB
- personal_tracker.html: 21KB
- calendar_dashboard.html: 18KB
- **Total:** 146KB (loaded once, cached)

---

## 📱 Mobile Usage

**Phone Access:**
1. Go to: https://dccodoceo-creator.github.io/acktib-sales-system/
2. Bookmark the page
3. Optional: Add to home screen (iOS: Share → Add to Home Screen | Android: Menu → Install App)

**Best Mobile Practices:**
- Use during calls (Plan → Execute → Log)
- Review dashboard in morning briefing
- Journal in evening commute
- Check metrics on Sunday

---

## ❓ FAQ

**Q: Will my data sync across phone and Mac?**
A: No. Each device has separate localStorage. You can manually export/import if needed.

**Q: What happens if I clear browser cache?**
A: All data is lost. We recommend occasional exports (copy from DevTools Console).

**Q: Can I edit past entries?**
A: Yes. All tools let you view/edit/delete historical entries.

**Q: Is my data private?**
A: Completely. All data stays on your device. No server access.

**Q: Can I add custom metrics?**
A: Yes. Metrics Dashboard accepts custom entries. Objections and Journal can be customized too.

**Q: What if I miss a day?**
A: Just pick up the next day. The system is flexible—consistency matters more than perfection.

---

## 🎓 Learning Path

### **Week 1: Foundation**
- ✅ Complete AM/PM Plans daily
- ✅ Log metrics
- ✅ Open Dashboard each morning

### **Week 2: Depth**
- ✅ Add 10+ objections to Playbook
- ✅ Complete Friday Journal
- ✅ Review weekly metrics

### **Week 3: Reflection**
- ✅ Complete Sunday Journal
- ✅ Update Personal Tracker skills
- ✅ Identify patterns in metrics

### **Week 4: Optimization**
- ✅ Review Playbook effectiveness
- ✅ Update low-performing scripts
- ✅ Plan next month's focus

---

## 📞 Support

**Questions about:**
- **How to use a tool?** → See the tool's description above
- **Data storage?** → See "Data Storage & Privacy" section
- **Workflow setup?** → See "Recommended Daily Workflow" section
- **Integration?** → See "Integration with Other Tools" section

---

## 🚀 Version History

**v2.0** (Current)
- Added real-time dashboard with live stats
- Enhanced mobile responsiveness
- GitHub Pages deployment
- Comprehensive documentation

**v1.0**
- Initial 6-tool system
- localStorage persistence
- Responsive design

---

## 📝 License

Personal use - Copyright 2026

---

**Created for:** High-performance sales professionals who want data-driven growth and operational excellence.

**Philosophy:** Simple tools, consistent execution, exponential growth.

---

**Start your journey:** [Open Dashboard](https://dccodoceo-creator.github.io/acktib-sales-system/) → Plan AM → Execute → Review → Grow

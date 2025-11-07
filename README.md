# 📅 FAFSA Timeline Generator Tool

**Never miss a financial aid deadline again**

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-production-success.svg)
![React](https://img.shields.io/badge/React-19.1.1-61DAFB?logo=react)

---

## 📋 Overview

The **FAFSA Timeline Generator Tool** is a personalized financial aid planning application that creates custom FAFSA timelines with deadlines, reminders, and milestones tailored to each student's unique situation. This interactive tool helps students navigate the complex FAFSA process by providing state-specific deadlines, student-type-specific guidance, and special circumstance handling.

Built by **My College Finance**, this tool eliminates the stress and confusion of FAFSA deadlines by generating a personalized action plan that tracks your progress, sends reminders, and ensures you maximize your financial aid opportunities. The application adapts to your academic year, student type (high school senior, current college student, graduate student, or adult learner), state requirements, and special circumstances like divorced parents or independent student status.

Whether you're a first-time FAFSA filer or renewing your application, the FAFSA Timeline Generator provides a clear roadmap with priority deadlines color-coded by urgency, progress tracking, exportable timelines (PDF and calendar formats), and educational tips to help you succeed.

**🚀 Try it out:** [https://thiinkmg.github.io/FAFSA-Timeline-Generator-Tool/](https://thiinkmg.github.io/FAFSA-Timeline-Generator-Tool/)

---

## ✨ Features

- **Personalized Timeline Generation** - Creates custom FAFSA timelines based on academic year (2025-26 through 2028-29), student type, and state
- **Multi-Student Type Support** - Tailored timelines for high school seniors, current college students, graduate students, and adult learners
- **State-Specific Deadlines** - Automatically includes state-specific aid deadlines for California (CADAA), Texas (TASFA), and New York (TAP)
- **Special Circumstances Handling** - Adds custom deadlines for divorced/remarried parents, independent students, and financial aid appeals
- **Visual Timeline Interface** - Color-coded urgency indicators (red for critical ≤7 days, amber for 8-30 days, blue for 30+ days, green for completed)
- **Progress Tracking** - Check off completed tasks and track your overall progress percentage with auto-save to localStorage
- **Deadline Countdown** - Real-time countdown to your next upcoming deadline with days remaining
- **Personal Notes** - Add custom notes to each deadline to track documentation, questions, or status updates
- **PDF Export** - Download a professionally formatted PDF timeline with MCF branding for printing or sharing
- **Calendar Export (.ics)** - Export your timeline to Google Calendar, Outlook, Apple Calendar, or any calendar app with automatic reminders
- **Dark Mode Support** - Toggle between light and dark themes with enhanced readability in both modes
- **localStorage Persistence** - Your timeline and progress are automatically saved locally and restored when you return
- **Responsive Mobile Design** - Optimized for all devices from mobile phones to desktop screens
- **Educational Pro Tips** - Contextual advice and best practices for FAFSA completion and financial aid maximization

---

## 🎯 Educational Value

The FAFSA Timeline Generator Tool serves as an essential educational resource for students and families navigating the federal financial aid process. This tool teaches students how to:

- **Plan Financial Aid Applications Strategically**: Understand the importance of early FAFSA submission and how priority deadlines affect aid availability
- **Navigate State-Specific Requirements**: Learn about state financial aid programs (CADAA, TASFA, TAP) and their unique deadlines
- **Understand Student Type Differences**: Recognize how timeline requirements differ for high school seniors, current students, graduate students, and adult learners
- **Manage Complex Family Situations**: Handle special circumstances like divorced parents, remarried contributors, and independent student status documentation
- **Track Multiple Deadlines Simultaneously**: Develop organizational skills by managing federal, state, and institutional deadlines in one place
- **Maximize Financial Aid Opportunities**: Learn strategic timing for FAFSA submission, tax document preparation, and award letter comparison
- **Build Financial Planning Habits**: Create sustainable routines for annual FAFSA renewal and ongoing financial aid management

The application covers critical topics in financial aid administration including FAFSA opening dates, priority deadlines, state aid programs, institutional aid timelines, award letter analysis, and National Decision Day. By providing visual urgency indicators and progress tracking, it reduces anxiety and ensures students can confidently complete the FAFSA process without missing critical deadlines.

---

## 🚀 Getting Started

### Prerequisites

- **Modern Web Browser**: Chrome 90+, Firefox 88+, Safari 14+, or Edge 90+
- **For Local Development**: Node.js 18+ and npm 9+

### Installation

#### Option 1: Use Online (Recommended)

Simply visit the live application:

**🌐 [https://thiinkmg.github.io/FAFSA-Timeline-Generator-Tool/](https://thiinkmg.github.io/FAFSA-Timeline-Generator-Tool/)**

No installation required! The app runs entirely in your browser and saves your data locally.

#### Option 2: Run Locally

```bash
# Clone the repository
git clone https://github.com/ThiinkMG/FAFSA-Timeline-Generator-Tool.git

# Navigate to project directory
cd FAFSA-Timeline-Generator-Tool

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at `http://localhost:5173`

### Usage

1. **Enter Your Information**: Provide your name, select your academic year, choose your student type, and select your state
2. **Specify Special Circumstances**: Indicate if you have divorced/remarried parents, independent student status, special financial circumstances, or plan to file an appeal
3. **Generate Your Timeline**: Click "Generate Timeline" to create your personalized FAFSA action plan
4. **Track Your Progress**: Check off completed deadlines as you work through them
5. **Add Personal Notes**: Click on any deadline to add notes about documentation collected, questions, or status updates
6. **Export Your Timeline**: Download a PDF for printing or export to your calendar app for automatic reminders

---

## 🛠️ Technical Details

### Built With

**Frontend Framework & Build Tools:**
- **React** 19.1.1 - Modern UI with concurrent features
- **TypeScript** 5.9.3 - Type-safe development
- **Vite** 7.1.7 - Lightning-fast build tool and dev server

**UI Component System:**
- **Radix UI Primitives** - Accessible component primitives
- **Lucide React** 0.553.0 - Icon library
- **Tailwind CSS** 3.4.18 - Utility-first styling

**Date & Time Management:**
- **date-fns** 4.1.0 - Modern date manipulation

**Export Capabilities:**
- **jsPDF** 3.0.3 - Professional PDF generation

### Browser Compatibility

- Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- Mobile browsers (iOS Safari 14+, Chrome Mobile 90+)

---

## 📱 Responsive Design

The FAFSA Timeline Generator is built with a **mobile-first approach** and adapts seamlessly to all screen sizes.

### Breakpoints

```css
/* Mobile (default) - 0px+ */
/* Small tablets (640px+) - sm: */
/* Tablets (768px+) - md: */
/* Desktop (1024px+) - lg: */
/* Large Desktop (1280px+) - xl: */
```

---

## 🎨 Customization

### MCF Brand Colors

```css
/* Primary Brand Colors */
--brand-blue: #012699;      /* Primary CTAs, headers */
--brand-green: #26e011;     /* Success states */
--brand-amber: #fdc003;     /* Warnings, highlights */
--brand-black: #000516;     /* Dark backgrounds */
```

### Dark Mode

Dark mode can be toggled with a button in the header and persists via localStorage.

---

## 🎓 Educational Use Cases

Perfect for:

- **High School Seniors**: First-time FAFSA filers navigating the college application process
- **Current College Students**: Renewing FAFSA applications annually
- **Graduate Students**: Managing FAFSA, assistantships, and fellowship deadlines
- **Adult Learners**: Non-traditional students returning to education
- **Students with Special Circumstances**: Complex family situations requiring appeals
- **Financial Aid Counselors**: Guiding multiple students through the FAFSA process

---

## ♿ Accessibility Features

The FAFSA Timeline Generator Tool is designed to meet **WCAG 2.1 Level AA** standards:

- ✅ Semantic HTML structure
- ✅ Full keyboard navigation
- ✅ Color contrast compliance (AA)
- ✅ Touch target sizing (44px minimum)
- ✅ ARIA labels on interactive elements
- ✅ Dark mode with enhanced contrast

---

## 🔧 Development

### Local Development Setup

```bash
git clone https://github.com/ThiinkMG/FAFSA-Timeline-Generator-Tool.git
cd FAFSA-Timeline-Generator-Tool
npm install
npm run dev
```

### File Structure

```
FAFSA-Timeline-Generator/
├── src/
│   ├── components/
│   │   ├── layout/           # Header, Footer
│   │   ├── forms/            # TimelineFormWizard
│   │   ├── timeline/         # TimelineVisualization, DeadlineCountdown
│   │   └── ui/               # Radix UI wrappers
│   ├── lib/
│   │   ├── timeline-data.ts  # Timeline database
│   │   ├── pdf-export.ts     # PDF generation
│   │   └── calendar-export.ts # .ics generation
│   ├── hooks/                # useLocalStorage
│   ├── types/                # TypeScript types
│   ├── App.tsx
│   └── index.css             # MCF theme
├── public/
├── index.html
└── vite.config.ts
```

### Building for Production

```bash
npm run build
npm run deploy
```

---

## 🤝 Contributing

We welcome contributions! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch
3. Make your changes with clear commits
4. Test across desktop and mobile
5. Submit a pull request

---

## 📞 Support

- **Email**: contact@mycollegefinance.com
- **Website**: [https://www.mycollegefinance.com/](https://www.mycollegefinance.com/)
- **Issues**: [GitHub Issues](https://github.com/ThiinkMG/FAFSA-Timeline-Generator-Tool/issues)

---

## 📜 License

Copyright © 2025 My College Finance. All rights reserved.

Licensed under the MIT License.

---

## 🙏 Acknowledgments

**Created by:** My College Finance Development Team

**In Partnership with:**
- Federal Student Aid (FSA)
- National Association of Student Financial Aid Administrators (NASFAA)
- State Financial Aid Agencies

---

## 🔗 Related Resources

### Other My College Finance Tools

- [50/30/20 Budget Calculator](https://thiinkmg.github.io/50-30-20-budget-calculator-v3/)
- [Savings Goal Calculator](https://thiinkmg.github.io/Savings-Goal-Calculator/)
- [FAFSA Household Support Worksheet](https://thiinkmg.github.io/FAFSA-Household-Size-and-Support-Worksheet/)
- [Federal School Directory Search Tool](https://thiinkmg.github.io/Federal-School-Directory-Search-Tool/)

### Official FAFSA Resources

- [FAFSA.gov](https://studentaid.gov/h/apply-for-aid/fafsa)
- [Federal Student Aid](https://studentaid.gov/)
- [IRS Data Retrieval Tool](https://studentaid.gov/help-center/answers/article/what-is-irs-drt)

### MCF Main Website

- [My College Finance Homepage](https://www.mycollegefinance.com/)
- [Privacy Policy](https://www.mycollegefinance.com/privacy-policy)
- [Terms of Service](https://www.mycollegefinance.com/terms-policy)
- [Social Media Hub](https://linktr.ee/mycollegefinance)

---

**Built with ❤️ by My College Finance**

*Empowering students to navigate financial aid with confidence*

[Get Started →](https://thiinkmg.github.io/FAFSA-Timeline-Generator-Tool/)

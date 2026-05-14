# AI, Fintech & Deep Tech — CBS Summer 2026

A comprehensive course on AI, Machine Learning, and Deep Tech in Finance and Business, taught at Copenhagen Business School.

**Course Code:** BA-BHAAI1115U  
**Credits:** 7.5 ECTS  
**Instructor:** Prabhu Venkatesh  
**Institution:** Copenhagen Business School

## Overview

This repository contains interactive presentation materials using Reveal.js, covering:

- **Week 1:** Foundations & Core Concepts
  - Day 1: AI, ML, NLP, GenAI & Agentic AI
  - Session 3: Data Governance
  - Session 4: Quantum Computing & Future Tech
  - Session 5: Synthesis & Integration

- **Week 2:** Applications & Implementation *(coming soon)*
- **Week 3:** Advanced Topics & Conclusion *(coming soon)*

## Getting Started

### View Online

The easiest way to access the course materials is through GitHub Pages:

1. Visit: **[https://yourusername.github.io/cbs-course](https://yourusername.github.io/cbs-course)**
2. Navigate using the sidebar or direct links to each session

### Run Locally

```bash
# Clone the repository
git clone https://github.com/yourusername/cbs-course.git
cd cbs-course

# Open in your browser
open index.html
# or for Windows:
start index.html
# or for Linux:
xdg-open index.html
```

## File Structure

```
cbs-course/
├── index.html                           # Main hub/landing page
├── CBS_W1_Day1.html                     # Week 1, Day 1 slides
├── CBS_W1_S3_Data_Governance.html       # Week 1, Session 3 slides
├── CBS_W1_S4_Quantum.html               # Week 1, Session 4 slides
├── CBS_W1_S5_Synthesis.html             # Week 1, Session 5 slides
├── README.md                            # This file
├── LICENSE                              # MIT License
└── .gitignore                           # Git ignore rules
```

## Features

### Interactive Presentations
- **Reveal.js 5.x** — Full-featured presentation framework
- **Smooth animations** — Professional transitions and effects
- **Responsive design** — Works on all devices
- **Navigation controls** — Keyboard and mouse support

### Visual Design
- **Dark theme** — Easy on the eyes for extended viewing
- **Custom color palette** — Teal, amber, coral, blue, and purple accents
- **Typography** — DM Sans and DM Mono fonts from Google Fonts
- **Modern components** — Cards, tags, stat rings, and interactive elements

### Course Hub
- **Centralized index** — Single entry point for all sessions
- **Quick navigation** — Jump to any week or session
- **Visual organization** — Color-coded by session type
- **Future-ready** — Placeholder slots for upcoming weeks

## Reveal.js Controls

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **Arrow keys** | Navigate slides |
| **Space** | Next slide |
| **S** | Show speaker notes |
| **F** | Full screen |
| **ESC** | Slide overview |
| **B** | Black screen |
| **?** | Show help |

### Mouse Controls
- Click to navigate forward
- Right-click for navigation menu
- Drag to zoom into slides

## Customization

### Update Session Links
To add new sessions, edit the session grid in `index.html`:

```html
<a href="CBS_W2_Day1.html" class="session-card s1">
  <div class="session-label">Day 1</div>
  <h3 class="session-title">Your Session Title</h3>
  <p class="session-description">Session description here.</p>
  <div class="session-meta">
    <span>Topic</span>
    <span class="session-arrow">→</span>
  </div>
</a>
```

### Modify Colors
Edit the CSS variables in the `<style>` section:

```css
:root {
  --c-teal: #5DCAA5;
  --c-amber: #EF9F27;
  --c-coral: #F0997B;
  --c-blue: #85B7EB;
  --c-purple: #AFA9EC;
}
```

### Enable GitHub Pages

1. Go to your repository **Settings**
2. Navigate to **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **root** folder
5. Click **Save**

Your site will be published at `https://yourusername.github.io/cbs-course`

## Dependencies

All dependencies are loaded from CDN:
- **Reveal.js** — from cdnjs.cloudflare.com
- **Google Fonts** — DM Sans and DM Mono
- **D3.js** — for data visualization (in some sessions)

No installation or build process required.

## Browser Support

Works best on:
- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- iOS Safari (iOS 13+)
- Chrome Mobile (Android 8+)

## License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use the course materials for educational purposes
- ✅ Modify and adapt the content
- ✅ Share with students and colleagues
- ✅ Host on your own server or GitHub Pages

## Contributing

Improvements and corrections are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit with clear messages (`git commit -m "Add: new feature"`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

## Support

### Questions or Issues?

- 📧 Email: prabhu@cbs.dk
- 💬 GitHub Issues: [Report a bug or request a feature](../../issues)
- 📚 Documentation: See relevant slide content for detailed explanations

### Common Issues

**Slides not loading?**
- Ensure all `.html` files are in the same directory
- Check that your internet connection is working (CDN resources)
- Try a different browser

**Navigation not working?**
- Refresh the page
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Ensure JavaScript is enabled

## Course Topics

### Week 1: Foundations & Core Concepts

#### Day 1: AI, ML, NLP, GenAI & Agentic AI
An introduction to the fundamental concepts and recent advances in artificial intelligence, including machine learning paradigms, natural language processing, generative AI systems, and autonomous agents.

#### Session 3: Data Governance
Exploring data management pipelines, governance frameworks, ethical considerations, privacy regulations (GDPR), and compliance in AI systems.

#### Session 4: Quantum Computing & Future Tech
Understanding quantum computing principles, potential applications in finance and cryptography, and strategic implications for deep tech investments.

#### Session 5: Synthesis & Integration
Integrating core concepts through case studies, practical applications, evaluation frameworks, and strategic decision-making for deep tech ventures.

---

**Last Updated:** Summer 2026  
**Repository:** [github.com/yourusername/cbs-course](https://github.com/yourusername/cbs-course)

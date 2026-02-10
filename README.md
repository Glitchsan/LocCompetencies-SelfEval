# Localization Management Core Competencies (LMCC) - Self-Evaluation Tool

A web-based self-assessment tool that helps localization professionals evaluate their competencies across seven key dimensions of localization management.

## About LMCC

The [Localization Management Core Competencies (LMCC) typology](https://l10ncompetencies.wordpress.com) is a hierarchy of localization knowledge and skills necessary for the professional practice of localization management. This self-evaluation tool provides an interactive way to:

- Assess your strengths across seven core dimensions
- Identify areas for professional development
- Discover career paths that match your competency profile
- Receive personalized recommendations for skill development

## The Seven Dimensions

1. **Language, Culture, & Communication** - Bilingualism, Cultural awareness, Effective communication
2. **Research & Critical Thinking** - Analytical skills, Independent learning, Feedback and evaluation
3. **Market Awareness** - Industry knowledge, Standards, Organizations, Market trends
4. **Subject Matter Expertise** - Data security, Legal knowledge, Industry-specific knowledge
5. **GILT** - Globalization, Internationalization, Localization, and Translation
6. **Technology** - General tech skills, Communication platforms, PM tools, CAT, DTP, Software/Games/Websites, MT, and more
7. **Management** - Stakeholder, Account, Project, Quality, Terminology, Production/Operations, and Program

## Features

- Interactive self-assessment with 1-5 rating scale
- Visual radar chart displaying competency scores
- Personalized career path recommendations
- Actionable next steps for professional development
- Responsive design for mobile and desktop
- Print-friendly results

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser

### Installation

1. Fork this repository

2. Clone the forked repository to your local machine:
```bash
git clone https://github.com/your username/LocCompetencies-SelfEval.git
```

3. Open `index.html` in your web browser locally using Live Preview

That's it! No build process or dependencies required.

## Localization

This project is designed to be localized into multiple languages. Currently available:
- English (en-US) ✅
- Spanish (es-MX) - Coming soon as a classroom activity

### How to Localize

1. Fork this repository
2. Copy `strings_en-us.json` and rename it to your target locale (e.g., `strings_es-mx.json`)
3. Translate all strings in the JSON file
4. Copy `index.html` and name the new file to match your locale (e.g., `LocCompetencies_es-MX.html`)
5. Update the `<html lang="">` attribute and file references
6. Test thoroughly
7. Submit a pull request!

For students in the Website Localization class: Spanish localization will be assigned as a hands-on project to practice real-world localization workflows.

### Scoring Logic

The scoring logic that is implemented to determine the career paths recommended is found in: `career-paths-config.json`
Though you do not need to make any changes to that file, we recommend that you review the scoring logic. Of course, you're free to make any adjustments that you believe are needed to make the scoring logic more accurate.

### CSS Styling

This repo contains two style sheets that reflect the styles of two brands: LocEssentials and UIC.
Switch between loading one style sheet or the other by updating this line in the html files:

```
<link rel="stylesheet" href="locessential-styles.css">
```

Experiment with adjusting the styles provided, or create your own brand new style sheet.

## Project Structure

```
.
├── index.html                     # Main HTML file (English)
├── LocCompetencies_es-MX.html     # Spanish HTML file (To be created by localizer)
├── strings_en-us.json             # English language strings
├── strings_es-mx.json             # Spanish language strings (To be created by localizer)
├── career-paths-config.json       # Scoring logic
├── resource-loader.js             # Resource loading and language switching
├── evaluation.js                  # Core application logic
├── locessential-styles.css        # LocEssentials brand styling
├── estilos-uic.css                # UIC styling
├── README.md                      # This file
└── LICENSE                        # MIT License
```

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) - For radar chart visualization

## Contributing

Contributions are welcome through pull requests to the main repo! Here are some ways you can help:

- **Localization**: Translate the tool into new languages
- **Bug fixes**: Report or fix any issues you find
- **Feature suggestions**: Propose new features or improvements
- **Documentation**: Improve the README or add code comments

### For Educators

This project is ideal for teaching:
- Website localization workflows
- JSON-based localization
- Git/GitHub collaboration
- HTML/CSS translation and localization
- Localization Quality Assurance (LQA)

Feel free to fork this project for your classroom activities!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

LocEssentials retains the copyright of the English contents of the repo.

We encourage you to credit yourself for producing the localization. You'll find an area in the repo where you can uncomment the attribution text.

## Credits

- **LMCC Framework**: Based on research in localization management competencies
- **LocEssentials**: Original concept and development
- **Contributors**: Learn about [contributing](contributing.md)

## Contact

For questions, suggestions, or if you'd like to see additional career paths added:
- Email: info@locessentials.com
- Website: [LocEssentials](https://locessentials.com)

## Acknowledgments

- Thank you to all localization professionals who provided feedback on the competency framework
- Special thanks to students and educators using this tool in their coursework

---

© 2026 LocEssentials

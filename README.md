An open-source portfolio website generator 

Project Description
The open-source Portfolio website generator is a website that allows users to create a personal portfolio website by entering their details through simple form.Then you pick a theme and Download a portfolio.


Features
-Fill in a form 
-Pick a theme 
-Download your portfolio


 Project Structure
portfolio-generator/
│
├── features/                        ← All features live here (one folder per contributor)
│   │
│   ├── landing/                     — feature/landing-page
│   │   └── index.html               Landing page (fully self-contained, inline styles)
│   │
│   ├── generator/                   👤 Contributor B — feature/generator
│   │   └── generator.html           3-step form + live preview + theme HTML generation
│   │
│   ├── themes/                      👤 Contributor C — feature/themes
│   │   ├── theme1.html              Minimal Clean — standalone demo
│   │   ├── theme2.html              Dark Bold — standalone demo
│   │   └── theme3.html              Colorful Creative — standalone demo
│   │
│   └── export/                      👤 Contributor D — feature/export
│       └── react js              Download logic — exposes window.downloadPortfolio()
│
├── README.md                        Hafsat Muttaka
├── CONTRIBUTING.md                  Mubarak Abiodun Muse
├── LICENSE.md                       Ibrahim Lawal
└── .github/
    └── workflows/
        └── ci.yml                   👤 Repository Manager — CI/CD pipeline

How to Run

No build step needed. Just open the files in a browser:

bash
# Clone the repo
git clone <your-repo-url>
cd portfolio-generator

# Open the landing page
open features/landing/index.html

# Or go directly to the generator
open features/generator/generator.html


 Team Roles & Members

**The Project Lead [] is responsible for oerall coordination of the project, monitoring project progress and activities and ensuring that the group follows the agreed workflow.
**Repository Manager (Fatima Bashir Umar) Responsible for Repo setup, managing access permisions and maintaining repository structure and branches.
**Maintainer(Fatima Bashir Umar) is responsible for performing issue tacking,Code quality,Supporting contributors during development assigned memebers 
**Code reviewers  (Halima Abdulkadir, Simpa Abdulganiu Onimisi and Kabir munir Ammani) are responsible for Pull request reviews,providing constructive feedback,requesting changes ere necessary before approval.
** code Contributors (Shehu Suleiman Sulaiman, Saleh Ahmad Tijjani, Ahmad Rufai Nurudeen, Suleiman Mukhtar,Maryam Shehu Jafar) responsible for `feature/landing-page`,`features/landing/index.html`,`feature/generator`,`features/generator/generator.html`,`feature/themes`,`features/themes/theme1,2,3.html`, `feature/export` | `features/export/export react js` |
**Contributor**  (Hafsat Muttaka) responsible for documentating README.md file
**Contributor** (Mubarak Abiodun Muse) responsible for documentating contributing.md file
**Contributor** (Ibraim Lawal) responsible for documentating license.md file



Technology used
- **HTML5** — Semantic markup, no frameworks
- **CSS3** — Inline per file, variables, grid, flexbox, animations
- **react js** 
- **GitHub Actions** — CI/CD: HTML lint + file validation


Contributing
See (CONTRIBUTING.md).

License
 see (LICENSE.md).

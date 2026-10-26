# The Matrix – Software Agency Landing Page

A one-page website for **The Matrix**, a made-up software development agency. It is built with plain HTML and CSS only (no JavaScript, no frameworks). The page includes:

- **Header**: a sticky navigation bar with the logo, links and a "Get Started" button. On small screens the links fold into a menu button.
- **Hero**: the main headline, a short description and two call-to-action buttons.
- **Services**: three service cards (Full Stack Website, Mobile App, DevOps). Each card opens a details pop-up, which works with hidden checkboxes instead of JavaScript.
- **Footer**: the brand, social links, site navigation and contact details.

## Students

- Mhmd Shami
- Eyad Manaa

## Project Structure

```
ex_3/
├── index.html          # Page markup
├── style.css           # All styles (theme variables, sections, responsive rules)
└── images/
    └── code-rain.svg   # Hero background image
```

## How to Run

No installation or build step is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/MhmdShamii/dg-04_ex2_github_training.git
   ```
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge or Safari).

Or, with the **Live Server** extension in VS Code, right-click `index.html` and choose **Open with Live Server**.

## Git Workflow

- `main`: stable, reviewed code
- `dev`: where features are combined
- `feature/*` and `fixes/*`: one branch per task, merged through a pull request

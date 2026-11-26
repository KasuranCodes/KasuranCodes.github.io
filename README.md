# **Max McGill's Portfolio**

A static GitHub Pages portfolio for software, robotics, microcontroller, graphics, and Linux-distribution projects.

**Live site:** [kasurancodes.github.io](https://kasurancodes.github.io/)

## Sections

| Section | Purpose |
| --- | --- |
| Home | Name, role, and primary navigation |
| Featured Work | Selected projects marked as featured |
| Work | Complete linked project collection |
| Early Stages | Concepts and projects still in development |
| About | Skills, interests, and project/engineering background |
| Contact | Social and professional links |

## Projects

Project cards are maintained in the `projects` and `earlyStageProjects` arrays in `index.html`.

| Project | Repository | Status |
| --- | --- | --- |
| Misty Robot | [Misty](https://github.com/KasuranCodes/Misty) | Experimental Python and robot integration |
| Roller Coaster Automation | [STM32-Rollercoaster](https://github.com/KasuranCodes/STM32-Rollercoaster) | STM32 HAL control prototype |
| StoryBoard | [StoryBoard](https://github.com/KasuranCodes/StoryBoard) | Early C/OpenGL rendering prototype |
| StoryBoard Headers | [StoryBoard-Headers](https://github.com/KasuranCodes/StoryBoard-Headers) | Reserved/shared headers repository |
| mOSs | [mOSs](https://github.com/KasuranCodes/mOSs) | Experimental Linux-distribution concept |
| ubuntu-decK | [ubuntu-decK](https://github.com/KasuranCodes/ubuntu-decK) | Active Kubuntu SteamOS-style installer |
| DIY Folding Handheld | No repository linked | Early concept |

## Repository Structure

```text
.
├── index.html              # Page content and project-card data
├── misty.html              # Misty project details
├── stm.html                # STM32 project details
├── storyboard.html         # StoryBoard project details
├── moss.html               # mOSs project details
├── handheld.html           # Folding-handheld concept
├── assets/
│   ├── css/main2.css       # Portfolio styles
│   └── js/main.js          # Page behavior
├── images/                 # Project and profile images
└── obselete/               # Retained earlier template pages
```

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Inline SVG background and decoration
- Font Awesome
- GitHub Pages static hosting

The site does not require a build step or JavaScript package manager.

## Local Preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

Relative image and page paths are designed for the repository root and should be preserved when deploying to GitHub Pages.

## Updating Projects

Edit the project arrays near `PROJECT CARDS` in `index.html`:

- `projects` contains cards in the Work section
- Set `featured: true` to also show a project in Featured Work
- `links` provides repository buttons
- `earlyStageProjects` contains cards in the Early Stages section

Project detail pages live beside `index.html`. Update both the card and its detail page when project status or repository information changes.

## Accessibility

The site includes controls for:

- High contrast
- Large text
- Highlight colors
- Reduced motion
- Light, dark, and green themes

Theme and accessibility behavior is implemented in the existing JavaScript and CSS.

## Deployment

This repository is deployed through GitHub Pages. Push changes to the default branch and confirm the repository Pages source settings in GitHub.

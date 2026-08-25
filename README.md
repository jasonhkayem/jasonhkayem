# Jason Hkayem — Portfolio

Personal portfolio site for **Jason Hkayem**, a Computer Science graduate (June 2026, Holy Spirit
University of Kaslik) and Machine Learning Engineer working on embedding, deep learning, and
graph-based recommendation systems.

**Live site:** https://jasonhkayem.github.io/jasonhkayem/

Static single-page site — plain HTML, CSS, and JavaScript. No build step, no dependencies to install.

## Sections

| Section | Contents |
| --- | --- |
| **Home** | Name, typed-animation role headline, links to Projects and CV, and GitHub / LinkedIn / email icons. |
| **About** | Current role, education, and the kind of work I'm looking for. |
| **Experience** | Machine Learning Engineer Intern at Anghami / OSN+ (June 2026 – Present) and Cloud AI/ML Engineer Intern at Zero&One (Summer 2025), with the certificate. |
| **Projects** | AI Triage Workflow, CloudQ, Stride, Post-COVID Analytics, Loan Approval Classification, AI Obesity Predictor — each linking to its GitHub repo, plus a live demo for Stride. |
| **Skills** | Programming, Machine Learning & AI, frameworks, MLOps & Cloud, data & analytics, BI & automation, spoken languages. |

## Tech

- **Markup / styling:** HTML5, CSS3, [Bootstrap 5](https://getbootstrap.com/)
- **Icons:** [Boxicons](https://boxicons.com/), [Bootstrap Icons](https://icons.getbootstrap.com/)
- **JavaScript:** [Typed.js](https://mattboldt.com/demos/typed-js/) for the headline animation,
  [Waypoints](http://imakewebthings.com/waypoints/) for scroll triggers, and `assets/js/main.js`
  for navigation, smooth scrolling, and the mobile menu
- **Fonts:** Open Sans, Raleway, and Poppins via Google Fonts

Everything except the fonts is vendored under `assets/vendor/`, so the site works offline.

## Layout

```
index.html               Whole site — every section lives here
portfolio.html           Legacy path; redirects to index.html
CV_Jason_Hkayem.pdf      CV, linked from the hero
assets/
  css/style.css          Active stylesheet
  js/main.js             Nav, smooth scroll, typed headline
  img/                   Certificate image
  vendor/                Bootstrap, Boxicons, Bootstrap Icons, Typed.js, Waypoints
```
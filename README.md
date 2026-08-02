# francisparwez.github.io

Personal portfolio site for **Francis Parwez** — Data Analyst with an MSc in Data Science and a background in full-stack development.

🔗 Live site: [francisparwez.github.io](https://francisparwez.github.io)

## About

The site is built around a "code editor" theme — sections are styled like files/tabs (`about.md`, `projects/`, `skills.json`, `contact.sh`) to reflect a data analyst who came up through software development.

It covers:

- **Hero intro** — quick pitch and links to GitHub, LinkedIn, and email, plus a downloadable Resume.
- **About** — background story: MERN stack developer → MSc in Data Science → BI/analytics focus.
- **Projects** — featured work, including:
  - *HR Analytics Dashboard* (Power BI, Power Query, DAX)
  - *Fantasy Premier League Dream-Team Predictor* (Python, Pandas, LightGBM, CatBoost)
- **Skills** — Data Analytics, SQL & Databases, Python, Software Development, and Soft Skills.
- **Contact** — a front-end contact form (needs to be wired up to a service such as Formspree or Netlify Forms to actually send messages) plus direct email/phone/LinkedIn links.

## Tech Stack

- HTML5, CSS3, JavaScript
- Hosted via GitHub Pages

*(Update this section with your actual framework/tooling if the site uses something more specific, e.g. React, a static site generator, or a CSS framework — I inferred this from the live page.)*

## Project Structure

```
.
├── index.html          # Main site markup
├── files/
│   └── Francis Parwez.pdf   # Downloadable Resume
├── images/
│   └── francis_parwez.png   # Tab Logo
└── README.md
```

*(Adjust this to match your real folder layout.)*

## Running Locally

Since this is a static site, no build step should be required:

```bash
git clone https://github.com/francisparwez/francisparwez.github.io.git
cd francisparwez.github.io
```

Then simply open `index.html` in your browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Visit `http://localhost:8000`.

## Deployment

This site is deployed via **GitHub Pages** directly from this repository. Any changes pushed to the default branch go live automatically at [francisparwez.github.io](https://francisparwez.github.io).

## Contact Form Setup

The contact form is currently front-end only. To make it functional, connect it to a service like:

- [Formspree](https://formspree.io/)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- A custom backend/API endpoint

## Contact

- **Email:** [francisparwez@gmail.com](mailto:francisparwez@gmail.com)
- **Phone:** [+92 324 3237197](tel:+923243237197)
- **LinkedIn:** [linkedin.com/in/francisparwez](https://www.linkedin.com/in/francisparwez/)
- **GitHub:** [github.com/francisparwez](https://github.com/francisparwez)

## License

© Francis Parwez. All rights reserved.

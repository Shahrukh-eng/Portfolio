# Shahrukh Khan | Data Scientist Portfolio

A responsive black-and-gold portfolio website that presents my projects, internships, certificates and contact details. It is built with plain HTML, CSS and JavaScript, so there is nothing to install.

**Live site:** https://Shahrukh-eng.github.io/Portfolio/

## Features

- Hero section with my photo, a short introduction and quick highlights
- Education, an animated CGPA gauge and my tech stack
- Two data science internships (Navodita Infotech and IISPR)
- Three ML projects, each linked to its GitHub repository
- Eight certificates, including Google AI Essentials, NPTEL (IIT Madras), the British Airways job simulation on Forage and Outskill
- Contact section with email, phone, LinkedIn, GitHub and a message form
- Works on desktop, tablet and mobile

## Projects featured

| Project | Repository |
|---|---|
| Flight Price Prediction | [flight_price_prediction](https://github.com/Shahrukh-eng/flight_price_prediction) |
| Market Sentiment vs Trader Behavior | [ds_shahrukh](https://github.com/Shahrukh-eng/ds_shahrukh) |
| Customer Churn Prediction | [customer-churn-prediction](https://github.com/Shahrukh-eng/customer-churn-prediction) |

## Built with

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript
- Google Fonts: Oxanium and Inter

## Project structure

```
Portfolio/
├── index.html   # the whole site: HTML, CSS, JS and my photo in one file
└── README.md
```

## Run it locally

1. Download or clone the repository.
2. Open `index.html` in any browser.

An internet connection is needed only for the Google Fonts. Without it, the page falls back to system fonts.

## Deploy with GitHub Pages

1. Upload `index.html` and this README to the repository.
2. Go to **Settings, then Pages**, and choose the `main` branch as the source.
3. Your site goes live in a minute or two.

## Customize it

- **Add a certificate:** search for `class="minis` in `index.html` and copy an existing `<div class="mini">` card.
- **Change contact details:** search for the email address or phone number and edit them.
- **Change colors:** edit the variables at the top of the `<style>` block (`--gold`, `--bg` and so on).
- **Replace the photo:** the photo is stored as a long `data:image/jpeg;base64,...` string in the `<img>` tag. Do not edit it by hand. Replace the whole string with a new one.

## Contact

- Email: shahrukhkhankhan275@gmail.com
- LinkedIn: https://www.linkedin.com/in/shahrukh-khan-740b5532a
- GitHub: https://github.com/Shahrukh-eng

&copy; 2026 Shahrukh Khan. All rights reserved.

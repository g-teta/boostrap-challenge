# Bootstrap-Challenge

**Instructions:**
In this bootstrap challenge you are tasked to replicate the web page shown in the project-demo file, using only bootstrap 5 (No JS or any other CSS Framework).

# Full Stack Conf

A one-page website for **Full Stack Conf**, a one-day JavaScript conference for students and beginners, organised by Paragraph in Kigali, Rwanda.

## What's on the page

- **Home**: hero section with "Register Now" and "See Speakers" buttons
- **About**: what the event is, timings (doors 8:30am, first talk 9:00am, finish 5:00pm) and the topics covered (MongoDB, Express, React, Node JS, ES2015, Babel)
- **Speakers**: Chris, Duice, Meghan and Kami
- **Schedule**: seven sessions from the 9:00am keynote to the 4:00pm Babel talk
- **Registration modal**: basic info, topic interests and payment details
- **Footer**: newsletter sign-up and links

## Tech

- Plain HTML, no build step
- [Bootstrap 5.3.3](https://getbootstrap.com/) (CSS and JS bundle) loaded from the jsDelivr CDN
- [Roboto](https://fonts.google.com/specimen/Roboto) from Google Fonts

## Project structure

```
index.html
assets/
  images/
    Chris.jpg
    Duice.jpg
    Meghan.jpg
    Kami.jpg
```

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000. An internet connection is needed for the CDN-hosted Bootstrap and fonts.

## Known gaps

- The registration and newsletter forms have no backend; submitting them does nothing yet.
- The payment fields are plain inputs, so no real card data should be collected until a proper payment provider is integrated.
- The expiration year dropdown starts at 2016 and ends at 2020, and the footer says 2018, so both need updating.
- The nav links in the footer (Community, Tracks, Other Confs) point to `#home`.

## Credits

Organised by Paragraph. &copy; Full Stack Conf & Paragraph.

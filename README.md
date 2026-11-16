# Spinoff

A slot-machine project idea generator. Hit **Roll** and get a random company or product paired with a random hobby or activity, like **Strava for rock climbing** or **Calendly for book clubs**. Save the ones you like and come back to them later.

## Features

- **Slot-machine roll:** the company and activity spin and land one after the other
- **Save ideas:** keep any combo in the **Saved Ideas** tab, and remove it when you're done with it
- **Editable lists:** open Settings (the gear icon, bottom left) to change the lists the roll draws from
  - Defaults: 200 companies and 300 activities
  - Search a list by typing in its box; if the item isn't there, press **Add** to create it
  - Remove items with the × on each chip, or reset a list to its defaults
- **Light and dark mode:** follows your device setting
- **Mobile friendly:** works on phones, and respects the reduced-motion setting

## Run it

There is nothing to install or build. It's a single static file.

1. Download or clone this repo
2. Open `index.html` in your browser

## Deploy with GitHub Pages

1. Push this folder to a GitHub repository
2. Go to **Settings > Pages**
3. Under **Build and deployment**, choose **Deploy from a branch**
4. Select your main branch and the `/ (root)` folder, then save
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` after a minute or two

## How it works

- Plain HTML, CSS, and JavaScript in one file, with no frameworks and no external requests
- Saved ideas and your custom lists are stored in your browser's `localStorage`, so they stay on that device and browser only. Clearing site data removes them.
- The default lists are the `companies` and `hobbies` arrays near the top of the script in `index.html`. Edit them there to change the defaults for everyone.

## Project structure

```
spinoff/
├── README.md
└── index.html   # the whole app
```
## UPDATES
11/15/26 - Added info popup explaining users premise of the app and how to use the functions

## Ideas for later

- Lock one side (company or activity) and re-roll only the other
- Filtering for type of activity or company
- Copy or export saved ideas
- Sync saved ideas across devices

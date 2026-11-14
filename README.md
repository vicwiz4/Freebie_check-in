# Freebie Check-in

**A simple game and asset offer hub for Epic Games Store, Steam, and Fab.**

Freebie Check-in is a lightweight, responsive webpage that brings links to three digital stores into one place. It helps you visit their offer pages and set a recurring reminder to check for new free games and assets.

## Features

- **Epic Games Store:** Open the Store section in the Epic Games Launcher, or open the free-games page in a browser.
- **Steam:** Open Store Specials in the Steam desktop app, or visit the same page in a browser.
- **Fab:** Open the Fab marketplace in a browser to browse free digital assets and review their licenses.
- **Weekly calendar reminder:** Choose a day and local time, then download an `.ics` calendar event that repeats weekly. Import it into a calendar app that supports `.ics` files. The page does not need to stay open for calendar reminders to work.
- **Responsive gaming theme:** A charcoal background, red and cyan accents, angular panels, and inline vector-style store marks adapt to desktop and mobile screens.

## How it works

The site is a single `index.html` file containing its HTML, CSS, and JavaScript. It needs no server, build step, framework, or external libraries. Open the file in a browser to use it locally, or publish it with GitHub Pages.

Store pages open only when you click their links. Your browser may ask permission before opening a desktop launcher. The Epic launcher link opens its Store section; its browser link goes directly to the free-games page.

## Privacy and claiming

The page does not request account credentials, read store listings, or collect store data. Offer discovery, license review, and claiming happen manually in each store. The reminder is generated in your browser as a calendar file.

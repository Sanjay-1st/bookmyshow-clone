# BookMyShow Clone

A front-end practice clone of the [BookMyShow](https://in.bookmyshow.com) homepage, built to practice Bootstrap layout and components.

## Tech stack
- HTML5
- Custom CSS (`style.css`)
- Bootstrap 5.0.2 (CDN)
- Bootstrap Icons 1.8.1 (CDN)

## Features recreated
- Two-tier responsive navbar (logo, search, city selector modal, sign-in, offcanvas login sidebar)
- Category navigation (Movies, Stream, Events, Plays, Sports, Activities, Buzz)
- Bootstrap carousel with promotional banners
- Movie/event card rows ("Recommended Movies", "Premieres", "Events Happening Near You")
- Footer with social links and copyright notice

## How to run
Open `index.html` directly in a browser. No build step or server required.

## Known limitations
- All images are hotlinked to BookMyShow's live CDN (`bmscdn.com`) — they will break if that CDN ever changes or blocks hotlinking.
- Most navigation links are placeholders (`href="#"`); only "Find a Car"-style links are not applicable here, but most nav items don't go anywhere real.
- No backend — this is a static front-end exercise, not a working booking site.

## Status
Practice/learning project. Not production-ready.

## Versioning
This project follows [Semantic Versioning](https://semver.org/). See `CHANGELOG.md` for release history.
`v0.1.0` is the preserved baseline captured before any further improvements.

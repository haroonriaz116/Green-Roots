# Green-Roots

A student-led recycling initiative website built for Westmount Secondary School. The site explains how to recycle correctly and keeps students engaged over time through a quiz, a personal impact calculator, a recycling log, a leaderboard, and a campus-wide progress dashboard.

## Pages

* Homepage (homepage.html) — Introduces Green Roots, explains how to sort waste correctly, highlights programs like Bottle Battle and Plant-a-Tree Day, answers common questions, and lets students sign a pledge to commit to the initiative.
* Quiz (quiz.html) — A recycling knowledge quiz that tests students on what goes in which bin.
* Tracker (tracker.html) — Lets students log the items they recycle.
* Impact Calculator (impact.html) — Translates a student's recycling activity into a personal environmental impact.
* Leaderboard (leaderboard.html) — Ranks grades or students by recycling activity to drive friendly competition.
* Dashboard (dashboard.html) — A campus-wide view of progress toward the school's overall diversion goals.

All six pages share a consistent navigation bar, so visitors can move between them freely.

## Tech stack

No build step, framework, or backend is required. Interactive features, such as the pledge counter on the homepage, persist data in the browser's session storage for demo purposes.

## Project structure

```
green-roots/
├── homepage.html
├── quiz.html
├── tracker.html
├── impact.html
├── leaderboard.html
├── dashboard.html
└── images/
    ├── hero-kids-recycling-bin.png
    ├── bin-guide-kids.png
    ├── program-bottle-battle.png
    ├── program-eco-monitor-club.png
    └── program-plant-a-tree.png
```

## Running it locally

No installation or server is required. Clone the repository and open homepage.html directly in a browser:

```
git clone https://github.com/your-username/green-roots.git
cd green-roots
open homepage.html      # or just double-click the file
```

For a closer-to-production experience, you can also serve the folder with any static file server, for example:

```
python3 -m http.server 8000
```

and then visit http://localhost:8000/homepage.html.

## Design notes

The site uses a green-toned palette throughout, built around a primary green (#16a34a) with light green backgrounds and accents, to feel approachable and on-theme for an environmental program aimed at students. Cards, pill-shaped buttons, and rounded corners keep the interface friendly, and a sticky navigation bar with a leaf emoji logo ties all six pages together.

## Contact

Haroon Riaz — haroonriaz116@gmail.com

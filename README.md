# Smart Train Finder

A simple web app to find train connections between Swiss cities using the free public API from https://transport.opendata.ch/.

Note:
Although the original task mentioned the Hamburg–Amsterdam route, I chose to use Swiss cities for the live implementation because:
- The DB Fahrplan API required registration and was not responsive (I encountered domain errors during testing).
- The Transport Open Data API (transport.opendata.ch) provides free, open, and reliable access to real-time train data within Switzerland.
- Using Swiss routes ensured a fully working, real-data-based frontend within the limited time constraints of the task.

For completeness, I also built a mock version simulating Hamburg → Amsterdam data, but the live demo is powered by real API data from Swiss routes to ensure functionality and accuracy.

## Features

- Select from multiple city pairs
- Choose one-way or roundtrip with nights stay
- Search for connections on selected dates
- Sort results by fastest or cheapest
- Responsive UI 

## API

Uses Transport Open Data API (https://transport.opendata.ch/) to fetch real-time Swiss train connections.

## Deployment

Deployed on Vercel: smart-train-finder-dkm9te9ra-bharath-suryas-projects.vercel.app

---

## Tech Stack

- HTML, CSS, JavaScript
- No backend required

 🎥 Demo Walkthrough: [Watch Video](https://drive.google.com/file/d/1gUorwCoWE7U-i4qqDQuXsQBK1OxChX-9/view?usp=drive_link)
 


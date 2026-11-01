# Neha's Arcade Portfolio

A retro-arcade personal portfolio for **Gavara Neha**, an AI and ML student who builds browser-native AI apps.

**Live site:** https://main.d3bjqq8je3ca9h.amplifyapp.com

Built for the AWS Student Builder Challenge: Build Your Tech Superpower.

## Creative feature: "Insert coin"

The hero has an **Insert coin** button with a visible hint. It turns on the camera, and [MediaPipe](https://ai.google.dev/edge/mediapipe) hand tracking runs fully in the browser. Hold an open palm up for about a second and a hidden bonus level opens.

- Nothing is recorded or uploaded.
- A **Click to unlock** button works without a camera, so navigation is never blocked.
- The camera needs HTTPS, which AWS Amplify provides.

## What's inside

- **Level 1, About:** who I am, with stats
- **Level 2, Skills:** languages, AI and data, build and ship
- **Coding scoreboard:** CodeChef, HackerRank, and problem-solving profiles
- **Level 3, Projects:** nine projects, each with a screenshot, tech stack, stats, and links
- **Trophy room:** certificates and badges, shown as "power-ups"
- **Player gallery:** behind-the-scenes photos
- **Bonus level:** the hidden level that the gesture unlocks

## Tech

A single static page: HTML, CSS, and vanilla JavaScript, with no build step. MediaPipe Tasks Vision is loaded in the browser from a CDN. Fonts are Press Start 2P and Space Mono from Google Fonts.

## AWS services

- **AWS Amplify Hosting:** deployed with a manual zip upload; the site is served over HTTPS.
- **AWS Budgets:** a $10 monthly cost budget with email alerts.

## Project structure

```
index.html      the whole site
images/         project screenshots, certificates, badges, and photos
```

## Run locally

Open `index.html` in a browser. The camera feature works best on `localhost` or HTTPS.

## Deploy

Zip `index.html` and the `images` folder (with `index.html` at the top level, not inside another folder) and upload the zip to AWS Amplify Hosting using manual deployment.

## Notes

Project screenshots, certificates, and badges belong to their respective projects and issuers.

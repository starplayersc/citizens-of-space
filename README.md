# Citizens of Space — Mock Status Page

A satirical incident status page demonstrating how a game studio *should* communicate with its community during major service outages — with transparency, professionalism, and consistent updates instead of silence and censorship.

## What Is This?

This project is a humorous but pointed critique of how **Citizens of Space** handles service degradation incidents. It mocks up what an ideal, player-respecting status page would look like: timestamped updates, named responders, technical detail, and hourly check-ins — even during non-working hours.

It contrasts sharply with the reality: vague platitudes, hours of radio silence, thread wipes, and community bans for expressing frustration.

## Live Site

Hosted via GitHub Pages: [https://starplayersc.github.io/citizens-of-space](https://starplayersc.github.io/citizens-of-space)

## Structure

```
public/
└── index.html   # The status page
```

## Deployment

The site is automatically deployed to GitHub Pages on every push to `main` via the included GitHub Actions workflow (`.github/workflows/deploy.yml`).

To set it up:
1. Go to **Settings → Pages** in your repository
2. Set the source to **GitHub Actions**
3. Push to `main` — the workflow handles the rest

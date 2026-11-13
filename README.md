# India OTT Releases

Independent, free Apple Calendar subscription for confirmed Indian OTT movie and web-series release dates.

**Live calendar (after GitHub Pages is enabled):** https://vihari23.github.io/Movie-OTT-/india-ott.ics

**Subscription landing page:** https://vihari23.github.io/Movie-OTT-/

## Setup

1. In **Settings → Pages**, set **Build and deployment → Source → GitHub Actions**.
2. The `Publish India OTT ICS` workflow publishes the site. It runs on push, daily at 15:00 UTC (8 AM Phoenix), and manually via the Actions tab.
3. In Apple Calendar, choose **File → New Calendar Subscription**, paste the live calendar URL, and choose automatic refresh. Do not import the ICS as a one-time download.

The feed includes titles, confirmed release dates, languages, streaming platforms, and source URLs from [Cinebuds](https://cinebuds.com/ott-release-dates/). Tentative or undated releases are excluded. Event time 8–9 AM America/Phoenix is a display slot, not the streaming premiere hour. Source availability and future dates can change. If automatic extraction fails, publication fails and the last successful feed is retained; check GitHub Actions for errors.

This public calendar is separate from Phoenix Panchangam and contains no personal events.

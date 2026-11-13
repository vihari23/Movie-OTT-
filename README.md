# India OTT Releases

Independent, free Apple Calendar subscription for confirmed Indian OTT movie and web-series release dates.

**Live subscription (works without GitHub Pages):** https://raw.githubusercontent.com/vihari23/Movie-OTT-/main/site/india-ott.ics

**Optional GitHub Pages address:** https://vihari23.github.io/Movie-OTT-/india-ott.ics

**Subscription landing page:** https://vihari23.github.io/Movie-OTT-/

## Setup

1. GitHub Actions runs the live Cinebuds fetch on push, daily at 15:00 UTC (8 AM Phoenix), and manually on demand. It commits the generated ICS to `site/india-ott.ics`, making the raw GitHub subscription link usable even before Pages is enabled.
2. In Apple Calendar, choose **File → New Calendar Subscription**, paste the live raw subscription URL, and choose automatic refresh. Do not import the ICS as a one-time download.
3. **Optional:** for a public website and shorter Pages subscription link, go to **Settings → Pages** and choose **Build and deployment → Source → GitHub Actions**. The next successful run will deploy Pages, too.

The feed includes titles, confirmed release dates, languages, streaming platforms, and source URLs from [Cinebuds](https://cinebuds.com/ott-release-dates/). Tentative or undated releases are excluded. Event time 8–9 AM America/Phoenix is a display slot, not the streaming premiere hour. Source availability and future dates can change. If automatic extraction fails, the scheduled run fails and the last successful committed feed is retained; check GitHub Actions for errors.

This public calendar is separate from Phoenix Panchangam and contains no personal events.

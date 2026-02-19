<br>
<p align="center">
  <strong style="font-size:2rem;">Vista Intelligence</strong>
</p>

<h1 align="center">Vista Intelligence</h1>

<p align="center">
  <em>A systems-level analysis of <strong>Vista Group International</strong> (NZX: VGL) — the technology infrastructure behind the global cinema industry.</em>
</p>

<p align="center">
  <a href="https://brunohart.github.io/vista-intelligence/">View Live</a>
</p>

---

## What This Is

Four interactive visualisations that decompose Vista Group's business from first principles — mapping how a single New Zealand company built the operating system for 5,500+ cinemas across 116 countries, and what that position means strategically.

This isn't a stock pitch. It's a structural analysis: how does value flow through the theatrical film industry, where does Vista sit in that flow, and what are the feedback loops that make the position defensible?

---

## The Visualisations

### Intelligence Dashboard
A multi-section dashboard covering Vista's full business context — 30-year company timeline, product ecosystem architecture, financial trajectory, global footprint, competitive positioning, and leadership structure. Built to answer: *what does this company actually do, and how well is it doing it?*

### Film Industry Value Chain
Maps Vista's 12 products across the 6 stages of the theatrical film value chain — from content licensing through exhibition to audience intelligence. Reveals the data flywheel: each stage feeds the next, and Vista's coverage creates compounding network effects that are invisible from any single product view.

### Financial Growth Charts
14 Chart.js visualisations tracking a decade of financial data — revenue composition, EBITDA margin expansion, SaaS transition metrics, ARR trajectory, and share price history. The story in the numbers: a company that nearly didn't survive COVID, rebuilt around cloud economics, and is now scaling toward 33-37% EBITDA margins.

### Landing Page
A minimal entry point linking to the three dashboards above.

---

## Key Numbers

| Metric | Value |
|---|---|
| Revenue (2024) | NZ$150M |
| ARR | NZ$145.6M |
| Recurring Revenue | 90% |
| Cinema Sites | 5,500+ |
| Countries | 116 |
| Market Share (large circuits) | 46% |
| Screens | 45,000+ |

---

## Systems Thinking Lens

The interesting question about Vista isn't *what* they sell — it's *why the system holds together*. Three structural observations:

**1. The data flywheel is the moat.**
Vista Cinema runs the theatre's POS and ticketing. That transaction data feeds Movio's audience analytics. Movio's insights drive studio marketing spend. Studios buy because the data is rich. The data is rich because Vista runs the POS. Each layer reinforces the others.

**2. Cloud migration is a one-way door.**
Vista Cloud isn't just a re-hosting — it's a platform shift that enables dynamic pricing, AI-driven segmentation, and real-time decisioning that were architecturally impossible on-premise. Every client that migrates becomes permanently stickier. The 60%+ cinema-level migration they've achieved creates switching costs that compound.

**3. Flicks is the consumer data layer the B2B stack needs.**
22M annual users generating explicit taste signals (ratings, watchlists, reviews) that no POS system can capture. This preference data completes the loop — connecting *what people watch* with *why they chose it* — and feeds back into Movio's 100M+ moviegoer profiles.

---

## Technical Notes

- All files are self-contained HTML — no build step, no dependencies to install
- Charts use [Chart.js](https://www.chartjs.org/) via CDN
- Dark theme throughout, responsive layouts
- Open any `.html` file directly in a browser, or deploy to GitHub Pages

---

## Deploy to GitHub Pages

This repo is configured for GitHub Pages. Once pushed:

1. Go to **Settings > Pages**
2. Set source to **Deploy from a branch**
3. Select **main** branch, root folder
4. The site will be live at `https://brunohart.github.io/vista-intelligence/`

---

<p align="center">
  <sub>Data sourced from NZX filings, investor presentations, and public records as of February 2026.</sub>
</p>

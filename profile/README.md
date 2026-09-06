## clearfetch

Small web data tools, published on [Apify Store](https://apify.com/clearfetch).

Each one does a single job, returns clean JSON with documented field names, needs no proxy or login, and bills
per result rather than per row written, so failures cost nothing.

### Tools

| | What it does | Price |
|---|---|---|
| [Tech Stack Detector](https://apify.com/clearfetch/tech-stack-detector) | What any website is built with: CMS, ecommerce platform, frameworks, analytics, CDN, hosting and email provider, with a version and the matching evidence for every detection | $0.02 per site |
| [Website Contact Extractor](https://apify.com/clearfetch/website-contact-extractor) | Emails, phone numbers in E.164, social profiles and postal addresses, after following the site's own contact and imprint pages | $0.004 per site |
| [Document Text Extractor](https://apify.com/clearfetch/document-text-extractor) | PDF, DOCX and HTML to text and markdown, with real line breaks, per-page text and metadata, and scanned files flagged rather than returned empty | $0.005 per document |
| [Flashscore Tennis Scraper](https://apify.com/clearfetch/flashscore-tennis-scraper) | ATP, WTA, ITF and Challenger matches with set and tiebreak scores, statistics and full point-by-point | $0.001 per match |
| [Flashscore Football Scraper](https://apify.com/clearfetch/flashscore-football-scraper) | Every league, with halves, extra time and shootouts, goals and assists, cards and substitutions | $0.001 per match |
| [Flashscore Basketball Scraper](https://apify.com/clearfetch/flashscore-basketball-scraper) | Quarter and overtime scores that add up to the total, plus the full statistics sheet | $0.001 per game |
| [Flashscore Baseball Scraper](https://apify.com/clearfetch/flashscore-baseball-scraper) | Full inning-by-inning line scores, with an unbatted final inning marked rather than reported as a zero | $0.001 per game |
| [Flashscore Hockey Scraper](https://apify.com/clearfetch/flashscore-hockey-scraper) | Period scores, and whether a game was settled in regulation, overtime or a shootout | $0.001 per game |

### How these are built

- **Clean, stable JSON.** Documented fields, ISO timestamps, and the untouched source record kept alongside the
  parsed one, so nothing is lost if a field is not mapped yet.
- **No proxies, no logins, no cookies.** If a site cannot be read with an ordinary HTTP request, there is no tool
  for it here.
- **You pay for results, not attempts.** Unreachable sites and dead IDs are written to your dataset so you can
  see what happened, and cost nothing.
- **Evidence, not assertions.** Where a tool makes a judgement, it shows what it matched on and how confident it
  is, so you can verify rather than trust.
- **Checked every morning.** A scheduled health check runs every tool against live data and fails loudly if one
  stops returning what it should, so breakage is found before a user finds it.

Source is public for the tools where it is useful to read. Bug reports and requests are welcome in the Issues tab
of any repository here, or on the Actor itself.

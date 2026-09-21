# The Woodwork Premier League

A static website that rebuilds the 2026/27 Premier League table using **woodwork hits** as each match score.

- More woodwork hits = 3 points
- Equal woodwork hits = 1 point each
- Fewer woodwork hits = 0 points
- Tiebreakers: woodwork difference, woodwork for, alphabetical

## Free live data
The page reads the latest available `matches.csv` and `teams.csv` from FPL Core Insights:
https://github.com/olbauday/FPL-Core-Insights

The upstream README says its dataset is refreshed twice daily. The page checks for the latest available gameweek every time somebody opens it.

## Publish free with GitHub Pages
1. Create a new public GitHub repository, e.g. `woodwork-premier-league`.
2. Upload `index.html` (README is optional) to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. GitHub will show the public URL after deployment.

No build tools, API key, server, or paid hosting required.

# Steam localisation debt: demonstration dataset

Snapshot collected on 7 October 2026 from Steam's public store and review endpoints and the SteamSpy API, for the FIT5145 (Monash University) Assignment 3 project *Localisation Debt: Measuring the Review-Sentiment Penalty of Unsupported Languages on Steam*.

| File | Rows | Content |
|---|---|---|
| `data/frame.csv` | 3,867 | SteamSpy sampling frame: titles with at least 2,000 reviews |
| `data/games.csv` | 299 | Store metadata for the stratified sample, including the supported-languages string |
| `data/lang_totals.csv` | 3,588 | Lifetime positive/negative review totals per game × review language |
| `data/reviews_sample.csv` | 321,284 | Up to 100 most recent reviews per game × language: verdict, playtime at review, purchase flags, timestamp |

No Steam IDs, persona names or review text are included.

Download everything: https://github.com/Mohidkz05/steam-localisation-debt-data/archive/refs/heads/main.zip

Sources: Steam `appdetails` and `appreviews` endpoints (https://store.steampowered.com), subject to the Steam Web API Terms of Use; SteamSpy API (https://steamspy.com/api.php).

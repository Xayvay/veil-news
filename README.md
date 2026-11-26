# veil-news

Public news feed for Veil of Chaos. The game reads `news.json` from this repo's raw URL.

Format (v1): `{"version":1,"updated":"YYYY-MM-DD","items":[{"id":"n-0001","date":"YYYY-MM-DD","title":"...","body":"..."}]}`
Plain text only; at most 20 items are shown, newest first; keep the file under 64 KB.
To post news: edit `news.json` and commit.

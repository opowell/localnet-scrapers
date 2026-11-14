# Localnet scrapers

The scraper source that Localnet, a browser extension that is a personal search engine, starts with. `source.json` lists
the repo of every scraper; Localnet reads what each one scrapes from its own `source.json`, and pulls a scraper's code only when it first
scrapes a page the scraper reads.

To add a scraper, give it a repo of its own (see any listed here) and add the repo's address to `sources`.

| Scraper | Reads | Repo |
| --- | --- | --- |
| Reddit | `reddit.com` | [localnet-scraper-reddit](https://github.com/opowell/localnet-scraper-reddit) |
| Hacker News | `news.ycombinator.com` | [localnet-scraper-hackernews](https://github.com/opowell/localnet-scraper-hackernews) |
| Hacker News Search | `hn.algolia.com` | [localnet-scraper-hackernews-search](https://github.com/opowell/localnet-scraper-hackernews-search) |
| The Guardian | `theguardian.com` | [localnet-scraper-guardian](https://github.com/opowell/localnet-scraper-guardian) |
| RedGIFs | `redgifs.com` | [localnet-scraper-redgifs](https://github.com/opowell/localnet-scraper-redgifs) |
| Literotica Story | `www.literotica.com/s/` | [localnet-scraper-literotica-story](https://github.com/opowell/localnet-scraper-literotica-story) |
| Literotica Tag | `tags.literotica.com` | [localnet-scraper-literotica-tag](https://github.com/opowell/localnet-scraper-literotica-tag) |
| Literotica Series | `www.literotica.com/series/se/` | [localnet-scraper-literotica-series](https://github.com/opowell/localnet-scraper-literotica-series) |
| Literotica Category | `www.literotica.com/c/` | [localnet-scraper-literotica-category](https://github.com/opowell/localnet-scraper-literotica-category) |
| Literotica Author | `www.literotica.com/authors/` | [localnet-scraper-literotica-author](https://github.com/opowell/localnet-scraper-literotica-author) |
| Literotica Search | `search.literotica.com` | [localnet-scraper-literotica-search](https://github.com/opowell/localnet-scraper-literotica-search) |
| GitHub | `github.com` | [localnet-scraper-github](https://github.com/opowell/localnet-scraper-github) |
| arXiv | `arxiv.org` | [localnet-scraper-arxiv](https://github.com/opowell/localnet-scraper-arxiv) |
| Simon Willison | `simonwillison.net` | [localnet-scraper-simonwillison](https://github.com/opowell/localnet-scraper-simonwillison) |
| Cloudflare Blog | `blog.cloudflare.com` | [localnet-scraper-cloudflare-blog](https://github.com/opowell/localnet-scraper-cloudflare-blog) |
| Microsoft Dev Blogs | `devblogs.microsoft.com` | [localnet-scraper-devblogs](https://github.com/opowell/localnet-scraper-devblogs) |
| John D. Cook | `johndcook.com` | [localnet-scraper-johndcook](https://github.com/opowell/localnet-scraper-johndcook) |
| Terence Tao | `terrytao.wordpress.com` | [localnet-scraper-terrytao](https://github.com/opowell/localnet-scraper-terrytao) |
| CNBC | `cnbc.com` | [localnet-scraper-cnbc](https://github.com/opowell/localnet-scraper-cnbc) |
| Business Insider | `businessinsider.com` | [localnet-scraper-businessinsider](https://github.com/opowell/localnet-scraper-businessinsider) |
| YouTube | `youtube.com` | [localnet-scraper-youtube](https://github.com/opowell/localnet-scraper-youtube) |
| TNAFlix | `tnaflix.com` | [localnet-scraper-tnaflix](https://github.com/opowell/localnet-scraper-tnaflix) |
| Google | `www.google.com/search` | [localnet-scraper-google](https://github.com/opowell/localnet-scraper-google) |
| Bing | `www.bing.com/search` | [localnet-scraper-bing](https://github.com/opowell/localnet-scraper-bing) |
| DuckDuckGo | `duckduckgo.com/` | [localnet-scraper-duckduckgo](https://github.com/opowell/localnet-scraper-duckduckgo) |
| Brave Search | `search.brave.com/search` | [localnet-scraper-brave-search](https://github.com/opowell/localnet-scraper-brave-search) |
| Yahoo | `search.yahoo.com/search` | [localnet-scraper-yahoo](https://github.com/opowell/localnet-scraper-yahoo) |
| Chess.com Fog of War | `chess.com/variants/fog-of-war` | [localnet-scraper-chesscom-fog-of-war](https://github.com/opowell/localnet-scraper-chesscom-fog-of-war) |
| Wikipedia | `wikipedia.org` | [localnet-scraper-mediawiki](https://github.com/opowell/localnet-scraper-mediawiki) |
| Wiktionary | `wiktionary.org` | [localnet-scraper-mediawiki](https://github.com/opowell/localnet-scraper-mediawiki) |
| Fandom | `fandom.com/wiki/` | [localnet-scraper-mediawiki](https://github.com/opowell/localnet-scraper-mediawiki) |
| BBC | `bbc.co` | [localnet-scraper-bbc](https://github.com/opowell/localnet-scraper-bbc) |
| The New York Times | `nytimes.com` | [localnet-scraper-nytimes](https://github.com/opowell/localnet-scraper-nytimes) |
| ESPN | `espn.com` | [localnet-scraper-espn](https://github.com/opowell/localnet-scraper-espn) |
| Yahoo News | `yahoo.com/news` | [localnet-scraper-yahoo-news](https://github.com/opowell/localnet-scraper-yahoo-news) |
| MSN | `msn.com` | [localnet-scraper-msn](https://github.com/opowell/localnet-scraper-msn) |
| Mashable | `mashable.com` | [localnet-scraper-mashable](https://github.com/opowell/localnet-scraper-mashable) |
| Globo | `globo.com` | [localnet-scraper-globo](https://github.com/opowell/localnet-scraper-globo) |
| UOL | `uol.com.br` | [localnet-scraper-uol](https://github.com/opowell/localnet-scraper-uol) |
| Interia | `interia.pl` | [localnet-scraper-interia](https://github.com/opowell/localnet-scraper-interia) |
| Cricbuzz | `cricbuzz.com` | [localnet-scraper-cricbuzz](https://github.com/opowell/localnet-scraper-cricbuzz) |
| ESPNcricinfo | `cricinfo.com` | [localnet-scraper-cricinfo](https://github.com/opowell/localnet-scraper-cricinfo) |
| Microsoft Learn | `learn.microsoft.com` | [localnet-scraper-microsoft-learn](https://github.com/opowell/localnet-scraper-microsoft-learn) |
| Apple Support | `support.apple.com` | [localnet-scraper-apple-support](https://github.com/opowell/localnet-scraper-apple-support) |
| NHS | `www.nhs.uk` | [localnet-scraper-nhs](https://github.com/opowell/localnet-scraper-nhs) |
| Mayo Clinic | `mayoclinic.org` | [localnet-scraper-mayoclinic](https://github.com/opowell/localnet-scraper-mayoclinic) |
| PubMed | `pubmed.ncbi.nlm.nih.gov` | [localnet-scraper-pubmed](https://github.com/opowell/localnet-scraper-pubmed) |
| Cambridge Dictionary | `dictionary.cambridge.org` | [localnet-scraper-cambridge-dictionary](https://github.com/opowell/localnet-scraper-cambridge-dictionary) |
| Steam | `store.steampowered.com` | [localnet-scraper-steam](https://github.com/opowell/localnet-scraper-steam) |
| Telegram | `t.me/s/` | [localnet-scraper-telegram](https://github.com/opowell/localnet-scraper-telegram) |
| Amazon | `www.amazon.` | [localnet-scraper-amazon](https://github.com/opowell/localnet-scraper-amazon) |

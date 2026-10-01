# Draftlight privacy policy

Draftlight runs on your PC next to League of Legends. It has no account, no analytics and no ads.
Everything it sends is listed under "What it sends, and to whom".

## What it reads

From the League client on your PC: your champion select, the players in your game and on the loading
screen, your match history and your ranked stats. Draftlight uses them to set your runes, summoner
spells and item set, to show the players in your game and to keep a history of your own games.

While a match runs, Draftlight watches for Ctrl+X and Tab to show its overlays. Every key goes on to
the game unchanged, and no keys are stored or sent anywhere.

## What it keeps on your PC

Your settings, your recent games with their scores, the Riot IDs of friends you queued with (to show
your results together), and a cache of champion data and pictures. The log file holds technical
events, not player names. All of this stays on your PC: the copy from GitHub keeps it in
`%LOCALAPPDATA%\Draftlight`, the Store version in its own folder under
`%LOCALAPPDATA%\Packages` (and in `%LOCALAPPDATA%\Draftlight` if you used the GitHub copy before).

Uninstalling the Store version removes its own folder. Files in `%LOCALAPPDATA%\Draftlight` stay until
you delete that folder.

## What it sends, and to whom

Lolalytics (lolalytics.com) gets the champion, lane and rank that Draftlight needs build and matchup
statistics for. No names or account details go along.

Riot Games (ddragon.leagueoflegends.com) is asked for the current game version.

Draftlight's own server (draftlight-riot.pages.dev, hosted at Cloudflare) gets the Riot IDs of the
players in your game once the loading screen starts. It asks the Riot Games API for their ranked
record for the season and passes the answer back. The server keeps an answer in memory for up to ten
minutes and counts requests per IP address for a minute, so its limits can't be used up. It writes
nothing to a log or a database. Riot's privacy notice covers what Riot does with the request.

If `config.json` holds a Riot API key of your own, Draftlight asks Riot directly and skips the server.

GitHub (api.github.com) is asked whether there is a newer version, only by the copy downloaded from
GitHub. The Store version gets its updates from the Microsoft Store.

## Your choices

Pause in the tray menu stops Draftlight from doing anything in champion select. Uninstalling
Draftlight and deleting the folders above removes everything it kept.

## Questions

Open an issue at https://github.com/M981/draftlight-releases/issues.

Last updated: 2 October 2026.

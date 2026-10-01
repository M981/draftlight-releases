# Draftlight privacy policy

Draftlight runs on your PC next to League of Legends. It has no account, no analytics and no ads, and
it sends nothing to its developer.

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

The Riot Games API gets the Riot IDs of the players in your game, but only when you have added your
own Riot API key, to look up their ranked record for the season. Riot's privacy notice covers what
Riot does with that request.

GitHub (api.github.com) is asked whether there is a newer version, only by the copy downloaded from
GitHub. The Store version gets its updates from the Microsoft Store.

## Your choices

Pause in the tray menu stops Draftlight from doing anything in champion select. Removing your Riot
API key from `config.json` stops the lookups at Riot. Uninstalling Draftlight and deleting the folders
above removes everything it kept.

## Questions

Open an issue at https://github.com/M981/draftlight-releases/issues.

Last updated: 1 October 2026.

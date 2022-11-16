# TheCookieMC API
Here you can find the documentation for TheCookieMC's API! All requests are sent through `api.thecookiemc.net`. The system currently only works with player UUIDs, not usernames. As the server is under active development, some API requests may be removed or changed. Updates to the API will be in announced in the [Discussions](https://github.com/TheCookieMC/API/discussions) section on github.
### Available Values: 
**{uuid}**: <br>
A Player's 36 Character "Unique User ID". This can be found by searching a player on sites like NameMC. This does not reset after username changes. 
<br>
<br>**{game}**: <br>
The Internal ID of the game you are searching for.
| **Game**      	| **ID**          	|
|---------------	|-----------------	|
| Beacon Battle 	| `beacon_battle` 	|
| Trapped       	| `trapped`       	|
| Nether Raid   	| `nether_raid`   	|
### Public API:
General Player Information: `api.thecookiemc.net/player/{uuid}`
<br>Player's Game Information: `api.thecookiemc.net/player/{uuid}/game/{game}`
<br>Game Leaderboard Information (Top 100): `api.thecookiemc.net/leaderboard/{game}`


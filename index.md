This page lists some of the current user experience issues with the Dota 2 arcade, and possible solutions that we believe Valve could implement to fix or improve them.

## 30 games requirement to use the Arcade

Players can no longer download Dota 2 just to play custom games on the Arcade; instead, they are now forced to play 30 games of Dota, even if their original interest lay in playing Auto Chess, or some other custom game. This has severely handicapped the ability of custom games to bring new players into the Dota 2 ecosystem, since many of them will simply see the restriction and leave. This was a band-aid solution to deal with bots, and was never replaced with a better, permanent one.

**Suggested solution**

Make the 30 game requirement opt-in instead of mandatory, on a custom game basis, by making it an option in the game’s addon settings (addoninfo.txt file). That way, games which are not under bot attack can be enjoyed by new players, and those which are can enable the 30-game bot protection.

## Hour-long ban for failing to ready up for a custom game

A 1 hour ban is given when a player fails to click accept on any custom game lobby. This is too severe a penalty for real players, and causes constant issues due to simple human errors.

To compound this issue, the penalty is applied even on 1-player lobbies. It is also exploitable if the lobby’s host is a griefer, since they can start the lobby early (before the proper amount of players for the game is reached), giving players the choice of either taking an 1 hour penalty for something out of their control, or wasting the sometimes several minutes they spent finding their current lobby so far.

**Suggested solution**

Do not punish players for not clicking the accept button if:
a) It is a single player lobby, or
b) The lobby does not have full players.

Also, scale the punishment like in regular dota: start with a 5 minute penalty, then 10 minutes, 30, 60, and so on. 

## Kicked players can rejoin lobbies instantly

Players who are kicked from lobbies can instantly rejoin them. This is exploited by bots and griefers to rejoin faster than anyone can kick them out.

**Suggested solution**

Make it so players cannot join a lobby they have been kicked from either for the duration of the lobby or for 5 minutes. Also, to avoid bots quickly joining and leaving a lobby in order to avoid being kicked from it, add a small cooldown (5 seconds would be enough) to a player’s ability to enter or leave a lobby (can’t leave if you just joined, can’t rejoin if you just left).

## Games auto-start when the last player joins

Griefers will join lobbies when they are missing a single player, causing the game to auto-start. This causes the other players to be trapped with the griefer, since they cannot decline (as that would only grant them a 1-hour arcade ban). Bots are especially effective at this type of griefing, for obvious reasons.

**Suggested solution**

Add a 5 second countdown to game start so that hosts will have a chance to kick out griefers that try to sneak in. Players should NOT be able to leave the lobby during this countdown - it should serve strictly for the host to be able to kick bad actors. If that happens, the lobby should stop the countdown and go back to its previous state (waiting for players).

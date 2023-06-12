# Eterna Bot Docs

Welcome to the docs for the Eterna-Bot from the Eternaments server! Take a look around by using the chapter view icon in the top left of the README preview. 

## Basic Commands

`/calendar`: Displays the currently set calendar for the year. Outlines tournament kickoffs, finals, and so forth.

`/staff`: Shows the staff page for all of us who work at Eternaments. Use this if you're looking for someone specific from a certain department!

`/showteam [teamname: ]`: Fill in the `teamname` attribute with the team page that you'd like to display, such as ("Tech and Design").

## Personal Commands
### These commands are meant for managing and viewing your own profile and other user's profiles.

`/createplayerprofile`: You must fill out the following form to create a profile. Don't worry, this won't be permanent! You can change this at any time with the following command. ***A PROFILE IS REQUIRED FOR MULTIPLE OTHER COMMANDS***.

![createProfileModal](https://github.com/Warrior312/eterna-bot-documentation/assets/87901386/6085bdb1-7ca7-4aaa-8589-ba7506ac3459)


<br>
<br>

`/editplayerprofile`: Edit your current player profile registered with Eternaments. This command uses the same form as the one pictured above.


`/etplayer [user]`: Displays the mentioned user's profile within the active channel.



## Team Commands
### These commands are meant for team members and their captains. Keep note, some commands require captiancy to execute.

`/createteam`:Creates a team for the specified league. League name is case-sensitive.
<br>

![createTeamModal](photos/teamcreate.PNG)

<br>

`/disbandteam`: Disbands a team of your choosing. You MUST be the captain of a team to disband it. League names are case-sensitive, make sure you take care of it properly.

<br>

![disbandModal](photos/disbandmodal.PNG)

<br>

`/jointeam`: Sends a request to the captain of the team specified. The captain may approve or deny this request, and may supply a reason which will be sent to you in DMS.

<br>

`/leaveteam`: Leaves the team specified (if you are actively rostered on that team). Alerts all team members to this change.

## Match Commands
### Note: Each of these commands requires the `@EternaTeam` role.

<br>

`/genmatches`: Generates matches for all teams in all game groups. May require manual resolution. There are three outcomes of this command, each detailed below.

**ERROR #1**

<br>

![error](photos/error.png)

To resolve this error, you must have more than 1 team in the league registered with the bot. In this case, there is only one team registered to play in the Rocket League 

<br>

**ERROR #2: Resolution Requried**

![resolve](photos/resolve.png)

To resolve this error, you must choose a team that is within the dropdown box. This will match the unaccounted team with whichever team you choose, and is irreversible. Choose wisely.

<br>

**Success**

<br>

![success](photos/success.png)



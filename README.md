# HaxBall-Public-Yellow-Bot

<a href="https://discord.gg/t6Wvbqk"><img alt="Discord" src="https://img.shields.io/discord/536193210096156682?color=blue&label=DEVELOPER%27S%20DISCORD"></a>

## What is Yellow Bot
Yellow or in another words, obstacle course is a type of parkour, where the players pass the obstacles and kick the ball at the end. In our bot, players can make practices **(1.1)** on yellow maps and improve theirselves. We have added 7 different maps of miscellaneous difficulty levels as default. Of course, user can change them or add new ones.

Image 1.1 (A player is making practice at Beginner Yellow map)

![1 1](https://user-images.githubusercontent.com/68077608/158394557-c8bff7bf-943a-48dd-8248-2a37432511ee.PNG)

## Functionalities
Before talking about this section, let us indicate that this bot will be separated in different versions to let users to choose one or more of them. So, let's take a look at what the versions have (or will be having):

### Version 1
* Automatic map change system (both with timer and dependent of a goal scored)
* Dynamic content (pre-defined color, font, sound and messages)
* Language switch possibility (**tr** and **en**) **(2.1)**
* Map change by command (admin only - see **commands** section)
* Possibility to see map list (admin only) and map informations
* Speed counter **(2.2)**
* Simple logging system

Image 2.1 (A player is trying to change their language)

![2 1](https://user-images.githubusercontent.com/68077608/158397903-26f74825-c2f5-4e31-922d-6b3dd372e833.PNG)

Image 2.2 (Speed is shown on player avatar)

![2 2](https://user-images.githubusercontent.com/68077608/158397907-47f2f178-24e0-4515-abab-4286dd00feac.PNG)

## Commands
Of course we manage our rooms with some commands. For example, map changing, speed status changing etc. So, without further ado, let's take a look at the commands:

* !admin: Changes the player's admin status.
* !commands: Shows the available commands. **(3.1)**
* !discord: Shows the discord address. User can adjust it through the scripts.
* !lang: Switches the language of the player with given language code. If there are no languages corresponding with the given code, then a warning is displayed.
* !mapinfo: Displays the information (its name and ID) about the current map.
* !maplist: Displays the map list (name and ID). **(admin only)** **(3.2)**
* !mapload [ID]: Loads the map with given ID. If there are no maps corresponding with the given ID, then a warning is displayed. **(3.3)**
* !speed: Turns the speed on/off. When **ON**, player can see their speed during the race.

Image 3.1 (Commands are being displayed)

![3 1](https://user-images.githubusercontent.com/68077608/158399760-83cd618b-c421-4efe-ab81-ea00ac081d83.PNG)

Image 3.2 (Map list is being displayed)

![3 2](https://user-images.githubusercontent.com/68077608/158399777-a8a3931f-f0ea-43eb-90f1-46458602a97a.PNG)

Image 3.3 (An administrator is changing the current map by command)

![3 3](https://user-images.githubusercontent.com/68077608/158399806-906cfdf3-1e6f-4c21-8f8f-8a876a0b8437.PNG)

## Notes

* As you see above **(3.3)**, global announcements will be made in the room's own language.
* Step by step, we are going to add advanced functions and separate our bot into different versions. That's all for now, stay with us...

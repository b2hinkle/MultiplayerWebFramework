# MultiplayerWebFramework

An Engine agnostic framework for managing dedicated game servers.

*See it live at [https://mwfmanagementconsole.azurewebsites.net/](https://mwfmanagementconsole.azurewebsites.net/)*

## Demo
https://youtu.be/wAIStc3JcEE

## Problem Statement
It is very common among indie game developers to use listening servers when creating
online games. This is the quick and easy solution to implementing multiplayer games where one
player is the server and everyone connects to him/her. It is an appealing approach since players
don’t have to depend on the developer to manage the servers well. This approach however comes
with some disadvantages. Listening servers are limited to a small number of players, since the
game server has to do extra processing for the player (ie rendering). Listening servers also have a
lifetime dependent on the hosting player, meaning if the hosting player wants to quit, everyone
else is forced to. Listening servers are also limiting in that they can't reliably run anti-cheat logic
on the hosting player. The solution to these problems is to take the less easy approach and create
server processes manually. This requires organization if you want to maintain a game long term.
This is why I made a server management system for multiplayer games that allows indie
developers to easily manage dedicated servers.
(See documentation for how it was implemented)

## Full Diagram
![image](https://user-images.githubusercontent.com/7013902/131390434-9dfd03ee-c5b5-421a-9db6-4778d0ce8a92.png)





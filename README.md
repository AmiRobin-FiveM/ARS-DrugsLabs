# ARS Drugslabs

## Description

**ARS Drugslabs** is a dynamic and immersive drug lab system for FiveM, allowing players to process drugs within customizable labs across the map. Players can own multiple labs, and each lab can be upgraded to enhance efficiency. Labs can be sold by admins, and players can rob, raid, seize, and take over labs, all of which are fully configurable. The resource comes preconfigured with three types of labs: meth, coke, and weed, with the option to add more labs via the config file. The script is designed to work with both ESX and QB-Core frameworks. for selling drugs you can use ARS_Drugs script.

## Showcase

[![ARS Drugslabs Showcase](https://i.imgur.com/H7871Dw.png)](https://www.youtube.com/watch?v=hxpLnypYP0U)

## Features

- **Placeable Labs**: Labs can be placed anywhere on the map.
- **Drugs Missions**: Players can complete missions to earn drugs.
- **Multiple Lab Upgrades**: Players can upgrade labs to reduce processing time and increase efficiency.
- **Robbing Labs**: Players can rob labs owned by other players.
- **Raiding Labs**: Admins and law enforcement can raid labs.
- **Seizing Labs**: Labs can be seized by authorities.
- **Taking Over Labs**: Players can take over labs from other players.
- **Configurable**: Extensive configuration options to tailor the script to your server’s needs.

## Tebex:

Use the coupon code **10-OFF** and get $10 off your first subscription month.

[AmiRobin | (tebex.io)](https://amirobin.tebex.io/)

[ARS DrugsLabs ESX | (tebex.io)](https://amirobin.tebex.io/package/6532163)

[ARS DrugsLabs QB | (tebex.io)](https://amirobin.tebex.io/package/6532164)

## Installation

1. **Download** the resource from Keymaster.
2. **Extract** the resource to your `resources` folder.
3. Add `ensure ars_drugslabs` to your `server.cfg`.
4. **Install** the SQL file to your database.
5. **Configure** the config file according to your server’s preferences.
6. **Start** the server.

## Configuration

The configuration file can be found in `ars_drugslabs/shared/`. The configuration file contains the following options:
For the lab supplies you will need to have "coke_brick", "meth_brick", "weed_brick" as a item in your server,
for the lab finished products you will need to have "coke_pooch", "meth_pooch", "weed_pooch" as a item in your server.
if you want you can change the item names in the config file.

## Commands

- `/createdruglab`: Create a drug lab.
- `/removedruglab [bucketid]`: Delete a drug lab. (bucketid = lab id)
- `/removecooldown [type]`: Remove the cooldown from a drug lab. (type = lastrobbed, lastraided, lasttakeover, lastmission, lastseized)

## Dependencies

This script requires the following dependencies to function correctly:

- [es_extended](https://github.com/esx-framework/es_extended) or [qb-core](https://github.com/qbcore-framework/qb-core)
- [oxmysql](https://github.com/overextended/oxmysql)
- [ox_lib](https://github.com/overextended/ox_lib)
- [ox_target](https://github.com/overextended/ox_target), [qb-target](https://github.com/qbcore-framework/qb-target), or [qtarget](https://github.com/overextended/qtarget)

## Notes

- **Support**: For support with this resource, please visit the [ARS Discord](https://discord.gg/ars).
- **Drug Selling**: This script dont have drug selling system, you can use [ARS_Drugs] or any other drug selling script.

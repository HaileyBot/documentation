---
description: >-
  All documented updates or changes to HaileyBot over time (these ChangeLogs are
  currently outdated)
---

# ChangeLogs

## 4.7.0

_Released on October 22nd, 2018_

#### Added

*  New command `$-beta` to apply to become a HaileyBot beta tester
  * Use `$-help beta` for more info

## 4.6.0

_Released on October 14th, 2018_

#### Added

* `$-emote` now has a new sub-command called `add`
  * Uploads the provided URL or attachment as an emoji on your server
  * Allows creation of animated emotes without needing nitro

## 4.5.0

_Released on October 11th, 2018_

#### Added

* Bypass option for `$-filter` so you can make the filter ignore users with specified roles

#### Changed

* Changed server icon based on poll results
* ModLog command now has a bypass option, so it won't log messages from specified channels

## 4.4.2

_Released on October 8th, 2018_

#### Added

* New`EULA` rank that comes before `Verified`

#### Changed

* Color of `Verified` rank changed to green

## 4.4.1

_Released on October 7th, 2018_

#### Changed

* ModLog icons are now colorblind-friendly
* `$-register` now has a more accurate invite link check
* `$-bump` now checks if the ad's invite link has expired

## 4.4.0

_Released on October 6th, 2018_

#### Added

* New `$-live channels` subcommand to create unjoinable voice channels that display server stats

#### Changed

* `#warning-log`  is now public and has been moved to the `MODERATION` category to provide an example of how it works
* `#welcome` has been renamed to `#member-log` and has been moved to the `MODERATION` category
* `#modlog-tutorial` has been renamed to `#moderation-tutorial`, and now provides much more information regarding different moderation commands
* Role colors have been edited

## 4.3.2

_Released on October 5th, 2018_

#### Added

* ModLog now logs channel edit events

#### Changed

* ModLog now logs any embeds included in deleted or edited messages
* Links sent to ModLog channels no longer embed their content

## 4.3.1

_Released on October 4th, 2018_

#### Added

* New tutorial channels have been created for Global Chat, Advertising, and ModLog

#### Changed

* ModLog channel has been made public to provide an example of the functionality
* EULA channel is now hidden for all users who have accepted it

## 4.3.0

_Released on October 3, 2018_

#### Added

* ModLog feature is now fully functional. Use `$-help modlog` for more information

## 4.2.1

_Released on October 2, 2018_

#### Changed

* `$-stats` now has a few additional statistics, and no more annoying descriptions
* Bot invite link switched from **bitly** to **rebrandly**. Pre-assigned permissions have been modified as well

## 4.2.0

_Released on September 29th, 2018_

#### Added

* `$-user` can now fetch data for _any_ user on Discord if you provide their ID. You're no longer limited to only users the bot shares a server with

#### Changed

* `$-stats` now uses an embed as well, and has a brief write-up for each statistic
* `$-bump` now sends your ad with more info, in a better-looking format

## 4.1.0

_Released on September 29th, 2018_

#### Added

* Any channel, role, or user mentions in global chat will be replaced with the actual name of the mentioned channel, role, or user
* New `$-emote` command for looking up info about an emote and getting a full-size image of it
* New `$-live` command will send a message containing your server's statistics. Whenever any of the statistics change, the message will be updated automatically

## 4.0.0

_Released on September 28th, 2018_

#### Changed

* Redesigned global message formatting to use embeds
  * Messages from the same user get grouped together if no other users spoke between them
  * Embed color reflects the user's highest rank, regardless of any custom ranks
  * Milestone announcements are posted in the footer of the embed

## 3.1.0

_Released on September 25th, 2018_

#### Changed

* Redesign of `$-server` command
* `$-help` command now works properly again \(broke after v3.0.0\)

## 3.0.0

_Released on September 24th, 2018_

#### Added

* HaileyBot now has a username and discriminator when speaking in global chat, same as everybody else

#### Changed

* Complete rewrite of the entire core
* Complete rewrite of every command

#### Removed

* All traces of `Discordie` package have been deleted due to deprecation. Bot will now run much faster and more reliably

## 2.3.0

_Released on September 23rd, 2018_

#### Added

* Account creation date and avatar are now included in `$-user`

#### Changed

* Complete redesign of `$-user` command
* Bot is now hosted on a faster, more reliable computer

#### Removed

* All music functions have been removed from HaileyBot due to latency problems
* Voice channel `HaileyBot Radio` has been deleted

## 2.2.4

_Released on September 22nd, 2018_

#### Added

* New staff rank for the global chat, so that staff of the [official server](https://server.haileybot.com) are easier to distinguish from normal users when speaking through the global chat.

#### Changed

* Modified `#frequently-asked`:
  * Edited layout
  * Added numbers to questions and answers for easy reference
  * Reworded some questions for better clarity
  * Rewrote some answers for better clarity

## 2.2.3

_Released on September 21st, 2018_

#### Changed

* `#info` has been rewritten to provide more accurate and up-to-date information about the bot

## 2.2.2

_Released on September 19th, 2018_

#### Added

* New channel category `GLOBAL`, containing both current global chats, and possibly future additions
* New channel category `RADIO`, to keep the radio channels separate from the `SPEAKABLE` category, since you aren't able to speak in them
* New channel `#frequently-asked` has answers to the most common questions I get about the bot
* New command `$-faq` brings you directly to `#frequently-asked` so you can get your answers

#### Changed

* `#global` has been renamed to `#global-general`

#### Removed

* `#announcements` has been removed due to lack of use caused by the `CHANGELOGS` category

## 2.2.1

_Released on September 9th, 2018_

#### Changed

* `$-addserver` has been renamed to `$-link`
* `$-delserver` has been renamed to `$-unlink`

## 2.2.0

_Released on September 8th, 2018_

#### Added

* NSFW global chat, separate from the normal one. Use `$-addserver nsfw` to connect a server. Channel must be set as `nsfw` for it to work properly

#### Changed

* Accepting the [EULA](https://docs.haileybot.com/eula) is no longer required to use the global chat. It is now only required for sending links and/or images, as well as using the NSFW global chat

## 2.1.0

_Released on September 7th, 2018_

#### Changed

* Full redesign of [official website](https://haileybot.github.io)

## 2.0.0

_Released on August 26th, 2018_

#### Added

* Instagram Profile: [@hailey.bot](https://www.instagram.com/hailey.bot)
* Email Address: [haileybot@hotmail.com](mailto://haileybot@hotmail.com)




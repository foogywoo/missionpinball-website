---
layout: post
author: jab
title: This Month in Pinball September 2018
---
What happened in MPF-land in September 2018?
This post will highlight changes in MPF, MPF-MC, MPF monitor, documentation
and the rest of the ecosystem.

# News

* [HotRod and OPP.. what happened?](https://openpinballproject.wordpress.com/2018/06/27/6-26-2018-hot-rod-and-opp-what-happened/) - Hugh from OPP
* [HotRod and OPP and MPF]({% post_url 2018-09-23-hothot-and-opp-and-mpf %}) - jab (as response to Hugh)
* [LISY35 for Bally/Stern machine between 1977 and 1985](https://pinside.com/pinball/forum/topic/lisy35-help-with-bally-lamp-driver-code-needed) - MPF will support this platform soon
* [MPF Stickers](https://groups.google.com/forum/#!topic/mpf-users/_Hfof-FKqcs)

# MPF Projects 

Some active publicly documented projects by MPF users.
 
* [The Crazy Mansion](https://pinside.com/pinball/forum/topic/the-crazy-mansion-by-the-pinball-amigos)
* [The Nightmare Before Christmas](https://pinside.com/pinball/forum/topic/the-nightmare-before-christmas)
* [Minions Pinball](https://pinside.com/pinball/forum/topic/we-are-building-a-minions-pinball-updates-every-friday)
* [The Last Starfighter](https://pinside.com/pinball/forum/topic/southern-california-homebrew-anyone-interested/)
* [Good vs Evil Head2Head](https://pinside.com/pinball/forum/topic/head2head-custom-pinball-machine-good-vs-evil)
* [Spaceballs - The Pin](https://pinside.com/pinball/forum/topic/spaceballs-the-pin/)
* [Queen Pinball](https://pinside.com/pinball/forum/topic/flash-retheme-project/)
* [Queen Pinball](https://pinside.com/pinball/forum/topic/flash-retheme-project/)

We know that there are a lot more projects. Let us know if you want to be listed here as well.

# Current stable release (0.50)

We released MPF 0.50.15 and MPF-MC 0.50.8 with bugfixes and backports.

## Changes

None

## Bugfixes

* [Fix mode events when starting/stopping mode from BCP](https://github.com/missionpinball/mpf/issues/1215) - jab based on report by Travis Martin (backport)
* [Fix display_light_player crash when used in mode](https://github.com/missionpinball/mpf/pull/1224) - jab (backport)

## Documentation

None

# Dev release (future 0.51)

We pushed MPF dev-2.

## Changes/New features

* [Support other channel orders than RGB for all RGB DMDs](https://github.com/missionpinball/mpf-mc/issues/345) - jab based on request from Cadrion
* [Prevent warnings during init and batch incandescant update for OPP](https://github.com/missionpinball/mpf/pull/1220) - jab
* [Improve FAST behaviour during MPF init](https://github.com/missionpinball/mpf/pull/1221) - jab
* [Entrance switch ignore window](https://github.com/missionpinball/mpf/pull/1216) - avanwinkle
* [Improved README.md for the MPF project](https://github.com/missionpinball/mpf/pull/1219) - austinbgill
* [Update kivy to version 1.10.1](https://github.com/missionpinball/mpf-mc/pull/346) - jab

## Bugfixes

* [Fix mode events when starting/stopping mode from BCP](https://github.com/missionpinball/mpf/issues/1215) - jab based on report by Travis Martin
* [Fix display_light_player crash when used in mode](https://github.com/missionpinball/mpf/pull/1224) - jab

## Documentation

* [Document appliance classes and common ground](https://github.com/missionpinball/mpf-docs/commit/44c15465db97108d93fad1637c43a3778afdd4aa) - jab
* [Added examples for PD-LED](https://github.com/missionpinball/mpf-docs/commit/a57ddb305abf8b4738e355143be1222d6c763b6b) - jab
* [Improved bonus mode documentation](https://github.com/missionpinball/mpf-docs/pull/173) - avanwinkle
* [Document ball and game end mode blocking](https://github.com/missionpinball/mpf-docs/commit/fd7112356a26413abe27a0e0cb3980f586f3a6c9) - jab inspired by Lynn
* [Extra ball based on score example](https://github.com/missionpinball/mpf-docs/commit/2d8e6b7d073f6904564896ca485b3f3c69951027) - jab based on example from Lynn
* [How to use high score mode in EMs](https://github.com/missionpinball/mpf-docs/commit/318541ee4349776e5fb4660fcd44b29104f1a842) - jab based on example from Lynn
* [Document RGB DMD channel_order parameter](https://github.com/missionpinball/mpf-docs/commit/a21bcae7b7be032c918a987fdb32cda8ee2a567e) - jab
* [Added example of game mode which increases multiplier when lanes are complete](https://github.com/missionpinball/mpf-docs/pull/176) - travisbmartin
* [No longer claim Python 3.4 support - it is EOL](https://github.com/missionpinball/mpf-docs/commit/1639e5b62f221b6a525b3ca39da6b68dd2d88752) - jab
* [Document PC power on/off](https://github.com/missionpinball/mpf-docs/commit/8bb7de3ce54153c8e7afbc3fdb992b13bb000409) - jab
* [Typos](https://github.com/missionpinball/mpf-docs/pull/177), [Typos](https://github.com/missionpinball/mpf-docs/pull/178) - travisbmartin 

Have a look at the [dev documentation](http://docs.missionpinball.org/en/dev/).

## Open PRs/Not landed yet

* [New OSC module](https://github.com/missionpinball/mpf/pull/1200) - jab
* [P-Roc libpinproc in separate thread (since it is currently blocking)](https://github.com/missionpinball/mpf/pull/1195) - jab
* [Change sound volume handling in sound_player/sound_loop_player](https://github.com/missionpinball/mpf-mc/pull/333) - qcapen

## Upcoming changes/Not landed yet

* [Support for the Pololu Tic stepper controller](https://github.com/missionpinball/mpf/issues/1217) - wolfmarsh
* More stepper and servo hardware - jab
* Moving slides/widget management to MPF from MPF-MC to improve the programming interface - jab
* Full support for LISY35

## New contributors

Welcome travisbmartin and austinbgill!

Did we forget anything? Please let us know.
Discussions in [MPF-Users](https://groups.google.com/forum/#!forum/mpf-users).
# RaceRoom Career

RaceRoom Career turns **RaceRoom Racing Experience** single races into a career. Pick a
series and a team, then race each round in RaceRoom; your results are picked up
automatically and the career carries on around them: championship standings, contracts
and offers from other teams, prize money and repair bills, Invitational events, emails
from your manager, team and rivals, and a race report after every round. It runs on your
own PC; nothing is uploaded anywhere.

This repository is for downloads and feedback only. RaceRoom Career is a test build:
expect rough edges, and please tell us what you find.

## Download

Get **RaceRoom-Career-win-x64.zip** from the [latest release](../../releases/latest).
Windows 10 or 11, 64-bit, with RaceRoom installed through Steam. Nothing else to install.

## Install

1. Unzip `RaceRoom-Career-win-x64.zip` anywhere (e.g. `Documents\RaceRoom Career app`).
2. Run **RaceRoom Career.exe**. On first run it installs itself to
   `%LOCALAPPDATA%\Programs\RaceRoom Career` and opens from there; running the unzipped
   exe again just opens the app.
   Windows SmartScreen will probably warn about an unknown app the first time, because the
   exe isn't signed: *More info → Run anyway*.
3. The app finds RaceRoom's results folder by itself
   (`Documents\My Games\SimBin\RaceRoom Racing Experience\UserData`). If you have more than
   one RaceRoom install, it uses the one with the most recent result. It only ever reads
   that folder. If it can't find one, use **Connect folder** to choose it.

## Racing a round

1. Start a new career: choose a series, a team and how many rounds. Only own some
   tracks? Untick the rest in **Settings** first, so the calendar only uses tracks you have.
2. The **Race** tab shows the next round: car and livery, track, number of opponents and
   AI difficulty. Press **Race** to start RaceRoom through Steam.
3. In RaceRoom, set that up under *Single Player → Single Race* and drive it to the flag.
4. Back in RaceRoom Career, the result appears on its own. A race that doesn't match the
   next round waits under *Results waiting for you* instead of being scored.

**Show on phone** puts a QR code on screen with the round's setup, to read on your phone
or tablet while you set the race up.

## Your data

Your career is saved in `Documents\RaceRoom Career\career.json`, with a backup of the
previous session in `career.backup.json`. **Settings → Export career** saves a copy
anywhere, and **Import career** loads one back.

To update, unzip the new version over the old folder and run **RaceRoom Career.exe**; the
app updates itself and your career stays.

The app needs an internet connection only for its fonts.

## Feedback

Found a bug or have an idea? [Open an issue](../../issues/new) and say which series and
round, what you did and what happened. A screenshot helps.

RaceRoom Career is a fan-made app, not affiliated with or endorsed by KW Studios or
RaceRoom.

# Sebarguh's Unofficial Submods for Just Natsuki

This is a home page that groups all my public submods for the DDLC mod *Just Natsuki*. Each submod lives in its own repository, linked below.

I was inspired by the work of Zhaumbie, who makes incredible submods too. Here is a direct link to his GitHub page: [Zhaumbie's Unofficial JN Submods](https://github.com/Zhaumbie/Zhaumbies-Unofficial-JN-Submods)

> **Unofficial.** These submods are not affiliated with, endorsed by, or supported by the Just Natsuki developers. Please don't ask the JN Team for help with them: open an issue in the relevant repository instead.

> **Everything here is in BETA.** Expect bugs and rough edges. Improvements, big and small, are planned for each submod.

---

## Games/Session Submods

- [**Drawing Session**]([link]): Tell Natsuki you're going to draw. Her dialogue changes with your drawing style (Beta)
- [**Chess**]([(https://github.com/Sebarguh/Chess-Game-with-Natsuki-)]): Play chess against Natsuki, with a hand-made board and pieces (Beta)
- [**Piano Session**]([link]): Play your own piano while Natsuki listens (Beta)

## Utilities "so cool!"

- [**More Exit Dialogues**]([link]): 15 new reasons for leaving the game, with random variants and a comment when you come back (Beta)
- [**Outfit Preview**]([link]): Live preview of each element while creating a custom outfit (Beta)
- **Music Control** *(Spotify / VLC / SoundCloud)*: In-game box to control playback and show the current track (Coming soon ;>, full setup tutorial in progress)

## UX/UI interface design

- [**Glass UI**]([link]): A translucent "glass" redesign of the game's boxes (be careful: the boxes are translucent, so text can be harder to read on some backgrounds) (Beta)

---

## Back up your `persistent` file

> **Always, always back up your `persistent` file before installing or updating any submod.**

The `persistent` file holds your long-term data (affinity, unlocks, settings, what Natsuki remembers). A bad install or a conflict between submods can corrupt it, and without a backup it cannot be recovered. So please never skip this step, or Natsuki will hold it against you.

### Back up

1. **Close the game completely and correctly.**
2. Open your Ren'Py save folder:
   - **Windows:** press `Win+R`, type `%appdata%\RenPy` and press Enter (or paste `%APPDATA%\RenPy\` in the File Explorer address bar)
   - **macOS:** `~/Library/RenPy/`
   - **Linux:** `~/.renpy/`
3. Open the Just Natsuki folder (named `JustNatsuki-` followed by a number).
4. Copy the file named **`persistent`** (no extension) to a safe place: another drive, a cloud folder, a USB stick. Copying the whole folder (saves + persistent) is even better.
5. Add the date to the name of your copy, e.g. `persistent_2026-11-15_backup`.

### Restore

1. Close the game.
2. Replace the `persistent` file in the save folder with your copy (rename it back to exactly `persistent`).
3. Launch the game.

The official FAQ covers this too: [Just Natsuki wiki: FAQ](https://github.com/Just-Natsuki-Team/NatsukiModDev/wiki/04:-FAQ#can-i-back-up-my-save-data--how-do-i-find-my-persistent).

---

## General installation

Each repository has its own instructions, but the basics are the same:

1. Back up your `persistent` file.
2. Download the submod from its repository (**Releases**, or **Code → Download ZIP**).
3. Close the game.
4. Copy the `.rpy` file(s) (and the image folder, if there is one) into `Just Natsuki/game/submods/` *(create it if needed)*.
5. Launch the game. The first launch may be slower while Ren'Py recompiles.

To remove a submod, close the game and delete its files from the submods folder. Restore your `persistent` backup if you want a fully clean state.

## Good to know

- **Install only what you want.** The submods are independent.
- **Conflicts are possible** between submods that touch the same menus or dialogues. If something breaks, remove the last submod you added.
- Compatibility is tested on Just Natsuki 1.3.5 with Ren'Py 6.99.12 only.

## Reporting a bug

Open an issue in the **repository of the submod concerned**, with your JN version, the other submods you use, what happened, and the `traceback.txt` if there is one.

## Transparency: AI assistance

For the submods in this collection, the **structure and code skeleton** were written with the help of an AI assistant. The **dialogues, the expressions and Natsuki's tone** were kept as faithful as possible to her character, and were written, reviewed and modified by me.

## Credits

- The team Salvato for Doki Doki Literature Club
- The [Just Natsuki Team](https://github.com/Just-Natsuki-Team/NatsukiModDev) for the game and its source.
- [Zhaumbie](https://github.com/Zhaumbie) for the inspiration.
- [Wowm](https://github.com/wowm03) for beta testing.
- You, for the support :>

<!-- "## Latest updates" section here at the first release. -->

ArchiTotem Plus - Totem Management Addon for WoW 1.12.1

Vanilla+ WoW private server addon for efficient totem management.
This is a fork of ArchiTotem, originally developed for the 1.12.1 client, with modifications including:

    Adjusted totem durations
    Implementation of the Totemic Call spell (destroys totems and resets their timer, but does not return mana)

📌 Features

✔️ Easy totem selection and ordering

✔️ Custom scaling and positioning

✔️ Quick totem destruction with Totemic Call


🔧 Installation

    Download the latest release from the repository.
    Extract the folder and place it in Interface/AddOns/.
    Restart WoW and enable the addon in the AddOns menu.

⚙️ Commands

Command	Description	Example

/at set <earth/fire/water/air> <1-x>	Sets how many totems of a specific element are displayed.	/at set fire 2 (Shows the bottom 2 fire totems)

/at direction <up/down>	Sets the direction in which totems pop up.	/at direction down

/at scale #	Changes the size of the buttons (1 = default).	/at scale 2 (Doubles size)

/at order <element> <element> <element> <element>	Sets the order of totem elements.	/at order fire earth air water

/at showall	Toggles showing all totems on mouseover.	/at showall

/at bottomcast	Moves cast totems to the bottom row.	/at bottomcast


🛠️ Modifications

    Custom Totem Durations: Adjusted to match Vanilla+ balance.
    Totemic Call Implementation: Destroys all placed totems, resets their timers.

📢 Notes

    Supports Vanilla WoW 1.12.1 private server.
    Feedback and contributions are welcome!

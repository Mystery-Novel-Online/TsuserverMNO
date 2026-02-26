# Moderator Commands

Comprehensive list of available moderator commands.

---

## Moderation Actions

| Command | Parameters | Description |
|----------|------------|-------------|
| `/ban` | `<IPID/IP>` | Bans the specified IPID/IP* |
| `/banhdid` | `<HDID>` | Bans the specified HDID* |
| `/unban` | `<IPID/IP>` | Unbans the specified IPID/IP. |
| `/unbanhdid` | `<HDID>` | Unbans the specified HDID. |
| `/showname_freeze` | - | Changes the ability of non-staff members of being able to change or remove their own shownames. |
| `/showname_nuke` | - | Clears all shownames from non-staff members. |

*HDID values are linked to their relevant IPID, so all actions will happen simultaneously. 

---

## Announcements

| Command | Parameters | Description |
|----------|------------|-------------|
| `/announce` | `<message>` | Sends a server-wide announcement. |
| `/gm` | `<message>` | Sends a server-wide message with a moderator tag via the OOC chat. |
| `/lm` | `<message>` | Sends an message in the current area with a moderator tag via the OOC chat. |

---

## Speech Modifiers

| Command | Parameters | Description |
|----------|------------|-------------|
| `/gimp` | `<ID/IPID>` | Gimps a target so that all their IC messages are replaced with a selection of preset messages. |
| `/ungimp` | `<ID/IPID>` | Removes the gimp effect from the targeted user. |
| `/disemvowel` | `<ID/IPID>` | Removes vowels from everything the target says. |
| `/undisemvowel` | `<ID/IPID>` | Restores vowels to the target user. |
| `/disemconsonant` | `<ID/IPID>` | Removes consonants from everything the target says. |
| `/undisemconsonant` | `<ID/IPID>` | Restores consonants to the target user. |
| `/remove_h` | `<ID/IPID>` | Removes the letter "h" from everything the target says. |
| `/unremove_h` | `<ID/IPID>` | Restores the letter "h" to the targer user. |

---

## Character Management

| Command | Parameters | Description |
|----------|------------|-------------|
| `/charselect` | `[ID]` | Kicks the targeted player back to the character select screen. If no ID is provided, targets yourself. |
| `/switch` | `<character>` | Switches you to the given character. If some other player in the area is using it, they will be forced to the character select screen. |

---

## Area Management

| Command | Parameters | Description |
|----------|------------|-------------|
| `/modlock` | - | Locks the current area, making it accessible to only moderators. GMs, CMs and normal users can not enter. |
| `/unlock` | - | Unlocks an area, provided the lock came as a result of /lock or /modlock. |
| `/bglock` | - | Toggles the background lock in the current area. |
| `/can_iniswap` | - | Changes the iniswap status in the current area. Even if iniswap at all is forbidden you can configure all-time allowed iniswaps in *iniswaps.yaml* |
| `/defaultarea` | `<area number>` | Sets the given area to be the area all future players join when they connect to the server. |
| `/lights` | `<on/off>` `[area1] [area2]` | Changes the light status in the provided areas to on or off. If no area is provided, target the current area even if the background or area is locked. Areas with lights turned off will have a dark background and will alter or restrict certain user features such as getarea, autopass, bleeding, look and sneaking.|



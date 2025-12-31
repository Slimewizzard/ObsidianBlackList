# Obsidian BlackList

A data-only addon designed specifically to provide shared and external player databases for the **Obsidian** player tracking addon.

## Download
https://github.com/Slimewizzard/Obsidian

## Purpose

`ObsidianBlackList` acts as a middleman between raw community data and your personal `Obsidian` database. It allows you to import thousands of records without cluttering your local `SavedVariables` until you choose to merge them.

## ObsidianBlackList 

this file is my own guild's masterlist that we use, shared for convenience. 

## File Structure

- **ObsidianBlackList.lua**: The Master List. Contains a shared database of flagged players maintained by the community or project leads.
- **External.lua**: Your Personal Import Shell. Use this file to copy-paste data from spreadsheets, discord, or other sources into the correct Lua format for one-click importing.

## Usage

1. Install this folder alongside the main `Obsidian` addon.
2. In-game, open the **Obsidian** interface.
3. Use the **M** (Master) or **E** (External) buttons to merge the respective lists into your personal database.
4. Alternatively, use the slash commands:
   - `/obsidianbl master`: Imports from the shared community list.
   - `/obsidianbl external`: Imports from your custom `External.lua` data.

## For Contributors

When updating the Master List, ensure the format follows the `Obsidian_External_Blacklist` table structure to maintain compatibility with the importer logic in `Obsidian.lua`.

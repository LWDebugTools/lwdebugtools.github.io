---
title: Console
---

# Console

The Console tab is the first built-in Debug Tools tab. It is designed to turn frequently used console commands into a personal, clickable command board.

---

## Search

The search field scans all enabled console commands in the running editor session.

Search behavior:

- Case-insensitive
- Sloppy matching is allowed
- Spaces are ignored for matching, so a search such as `a b c` can match a command whose letters appear in order with any number of characters between them

The results list shows:

- The command name
- The command's help text when available

---

## Create saved command buttons

To save a command as a button:

1. Search for the command
2. Select it from the results list
3. Click **Create console command button**

The command is added to the saved button list below the builder area.

---

## Run, reorder, and remove buttons

Saved buttons support these actions:

- Click the main button to run the command
- Click **Up** or **Down** to reorder it
- Click **Remove** to delete it from your saved list

Duplicate saved buttons for the same command are not added.

---

## Persistence

Saved Console buttons are stored automatically. There is no Save button.

Your button list is restored when you reopen the panel or restart the editor. Saved data lives in the project's `Saved/DebugTools/DebugToolsUserData.json` file.

See [User Data and Persistence](/customization/user-data) for more detail.

[← Back to tabs](/tabs)

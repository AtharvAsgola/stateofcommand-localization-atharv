# State of Command Localization

This repository contains the community translation files for **State of Command**.

Anyone is welcome to help improve translations or add support for new languages.

---

# How To Contribute

1. Open the `locales` folder
2. Select your language file
3. Click the pencil icon near the top-right
4. Edit translations
5. Click **Commit changes**
6. Open a Pull Request

To make a new file:

1. Open the `locales` folder
2. Click **Add file** near the top-right and select **Create new file**
3. Name the file using your language code (e.g., `en.txt`)
4. Paste the original text and add your translations
5. Click **Commit changes**
6. Open a Pull Request

> translate only the values after =.

No software installation is required.

---

# Translation Rules

Only edit the text after the `=` sign.

Example:

menu.button.start_game=Start Game

↓

menu.button.start_game=Commencer la partie

Do NOT modify the key names on the left side.

---

# IMPORTANT — Formatting Tokens

Some translations contain formatting tokens like:

%d
%s
%.1f
%%
%zu

These MUST remain unchanged or the game may break.

Example:

ui.tooltip.morale=Morale: %.1f

Correct translation:

ui.tooltip.morale=Morale : %.1f

Incorrect translation:

ui.tooltip.morale=Morale

---

# Comments

Lines starting with `#` are comments and provide translation context.

Example:

# Main Menu

These comments do not need translation.

---

# Encoding

All files should remain UTF-8 encoded.

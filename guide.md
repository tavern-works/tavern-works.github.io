---
title: User Guide
order: 2
---

# Overview

When you launch Tavern on a large screen, you'll see something like this:

![overview](assets/images/overview.webp)

There are three major sections of the app, each of which will be described in more detail below:

- The [Info Panel](#info-panel) is the section on the left side of the screen, which contains game master (GM) controls, character cards, and settings.

- The [Communication Panel](#communication-panel) is the section on the right side of the screen, which contains the character selector, the timeline of chat entries and dice rolls, and entry fields for both chat and dice rolls.

- The rest of the screen, between the two panels, is the [Map](#map).

> **Note:** On smaller screens, one or both of the panels may be hidden by default. You can toggle the visibility of the panels using the <span class="icon">info</span> or <span class="icon">comment</span> buttons at the bottom of the panel, or by using the <kbd>[</kbd> or <kbd>]</kbd> keyboard shortcuts.

# Info Panel

The Info Panel consists of three different sections:

- [GM Controls](#gm-controls)
- [Character Cards](#character-cards)
- [Settings](#settings)

## GM Controls

The **GM** checkbox allows you to toggle GM mode on and off.

In GM mode, you can add supporting characters (e.g., NPCs or monsters), rearrange the character cards (to track initiative order), and add and remove tokens from the map.

GM mode also affects which character cards you can see and how much information you can see onthem, as described below.

When you press the **Add Supporting** button, you will be presented with the following dialog:

![add supporting](assets/images/add_supporting.webp)

The search box will do a fuzzy search for matching entries, so it should find what you're looking for even with a typo or two.

Once you start typing, one of the entries in the list will be selected, and you can click/tap or use the <kbd>↑</kbd> and <kbd>↓</kbd> keys to select a different entry.

The **Randomize Name** checkbox will add a colorful descriptor to the name of the added character, which can be helpful to distinguish between multiple characters of the same kind. Of course, if you don't like the descriptor, you can always just change the name in the character sheet afterwards.

The **Quantity** selector allows you to add multiple characters at once in case the party runs across a group of friends (or foes).

## Character Cards

Character cards are the main way to get to any character-specific information. A typical character card looks something like this:

![character card](assets/images/character_card.webp)

On desktop computers, (while in [GM mode](#gm-controls)), you can drag the character's avatar (at the top left) onto the map to create a token. (If you're on a mobile device, a GM can still create tokens by long-pressing an empty square on the map.) Only a GM can see supporting characters that don't have a token on the map.

The hit point (HP) bar shows at a glance how many HP a character has remaining. Only a GM can see the HP bars for supporting characters.

Since characters can have temporary hit points, it is possible for the total hit point bar (green normal HP + blue temporary HP) to extend past the end of the outline indicating the character's maximum HP.

While it is possible to set a character's HP on their character sheet, there is also a quick edit field available by clicking/tapping on the underlined **HP** text:

![character card with hp editing](assets/images/character_card_hp.webp)

As with the character sheet, you can either enter a new HP value directly or use relative values such as `+3` or `-5`. If you enter a negative relative value, temporary HP will be removed before modifying normal HP.

For lead characters (i.e., PCs), if a character has a token, they will also have a <span class="icon">location_searching</span> button. Clicking/tapping on this button will center the map on their token and highlight it. Supporting characters with tokens can be located by clicking/tapping on their avatar.

Supporting characters have an <span class="icon">archive</span> button, which will move the character from the sorted list of character cards into a dedicated **Archived Characters** section at the bottom of the info panel (removing their token if one exists). Archived characters can be unarchived at any time by clicking/tapping the <span class="icon">unarchive</span> button.

The remaining buttons, such as <span class="icon">newsmode</span> or <span class="icon">backpack</span> will open corresponding sections of the character sheet. You can hover over them (on desktop) or long-press them (on mobile) to see which section they correspond to.

Finally, supporting characters each get a numeric keyboard shortcut, which allows you to focus their character card and either locate their token (by pressing the number again) or jump to one of the sheets of their character page. When you press the number, their card will change to help indicate the new keyboard shortcut options:

![focused character card](assets/images/character_card_focused.webp)

*Back to [Info Panel](#info-panel)* &mdash; *Jump to [Top](#overview)*

## Settings

# Communication Panel

# Map
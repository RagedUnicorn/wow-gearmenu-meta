# GearMenu
&nbsp;
![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/ragedunicorn_wow_banner.png)
&nbsp;
_GearMenu aims to help the player switch between items in and out of combat. When the player is in combat a combatqueue will take care of switching the item as soon as possible. It also allows you to define switching rules and keybinding slots._

## Providers

[![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/curseforge.svg)](https://www.curseforge.com/wow/addons/gearmenu)
[![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/wago.svg)](https://addons.wago.io/addons/gearmenu)

## What is GearMenu?

GearMenu's goal is to help the player switch between items on certain slots. Often players have items such as engineering items that have a one-time use followed by a long cooldown. After using them during a fight the player wants to switch back to a more useful item. While changing items during combat is not possible (with some exceptions such as weapons) GearMenu can help with switching them as soon as possible. When a player tries to switch an item during combat it will be put into the combatqueue and switched as soon as possible. If the player leaves combat for just a split second all the items in the combatqueue will be switched. For some classes this might be even easier because they can use spells such as rogue - vanish or hunter - feign death.

GearMenu supports World of Warcraft Classic Era, TBC Anniversary and Mists of Pandaria Classic, including Hardcore and Season of Discovery.

**Supported slots:**

* Head/Helmet slot
* Neck slot
* Shoulder slot
* Chest/Robe slot
* Waist/Belt slot
* Legs slot
* Feet/Boots slot
* Wrist/Bracers slot
* Hands slot
* First/Upper ring slot
* Second/Upper ring slot
* First/Upper trinket slot
* Second/Lower trinket slot
* Back/Cloak slot
* Main-hand slot
* Secondary-hand/Off-hand slot
* Ranged slot
* Ammo slot

## Issues

[![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/issues.svg)](https://github.com/RagedUnicorn/wow-classic-gearmenu/issues)

## Source

[![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/source.svg)](https://github.com/RagedUnicorn/wow-classic-gearmenu)

## Features of GearMenu

### Item switch for certain slots
With GearMenu it is easy to switch between items in supported slots. This is especially useful for engineering items that you wear for a certain amount of time and then switch back to your usual gear.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_switch_items.gif)

### CombatQueue
Certain items cannot be switched while the player is in combat. Weapons will be switched immediately whether the player is in combat or not. Other items that cannot be switched in combat will be enqueued in the combatqueue and switched as soon as possible. This is especially useful in PvP when you leave combat for a short time.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_combat_queue.gif)

**Note:** You can right-click any slot to clear the combatqueue for that slot

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_combat_queue_cancel.gif)

GearMenu also detects whether an itemswitch is possible even when out of combat. If you're switching an item while you're casting your mount or any other spell it will put the item in the combatqueue. As soon as the cast is over the item will be switched.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_combat_queue_cast.gif)

This is also the case if you cancel your cast.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_combat_queue_cast_cancel.gif)

### Quick Change

Quick change consists of rules that apply when certain items are used. The player can define rules for items that have a usable effect. An item might be immediately switched after use or only after a certain delay. Otherwise, the same rules for item switching apply. This means that if the user is in combat it will be moved to the combat queue and if he is out of combat the item will be immediately switched. See the options menu for defining new rules based on the item type.

**Note:** If an item has a buff effect, and you immediately change the item you will usually also lose its buff. In most cases it makes sense to set the delay to the duration of the buff

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_quick_change_add_rule.gif)

### Keybinding

GearMenu allows to keybind to every slot with a keybinding. Instead of having a keybind for every item that you have to remember you set it directly on the slot itself.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_keybinding.gif)

### Drag and drop support

GearMenu allows dragging and dropping items onto slots, removing them from slots, and even swapping items between slots. Drag and drop can be enabled or disabled in the options' menu.

#### Drag and drop between slots

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_drag_and_drop_slots.gif)

#### Drag and drop item to GearMenu

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_drag_and_drop_equip.gif)

#### Unequip item by drag and drop

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_drag_and_drop_unequip.gif)

### Combined Equipping

Slots such as trinket and ring slots have combined equipping enabled. This means that in addition to a left click on the item the player wishes to equip they also support right click. Slots that do not support combined equipping (which most don't) will normally equip any item whether it was left- or right-clicked. If the slot has combined equipping enabled a right click will instead put the chosen item into the opposite slot.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_combined_equip.gif)

### Unequip Items

Enable an empty slot in the changeMenu that allows for quicker and easier unequipping of items.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_unequip.gif)

### TrinketMenu

TrinketMenu allows the player to have all available trinkets and their status in view at all times. This makes it easier for the player to plan when to equip a trinket with a long cooldown. A left click will equip the trinket into the upper trinketslot and a right click will equip the item into the lower trinketslot.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_trinketmenu_demo.gif)

### Season of Discovery Rune Support

GearMenu has some support for displaying active runes on items that the player is either wearing or has in his inventory. This feature can be deactivated in the options' menu.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_rune_support.gif)

### Macro Support

If you prefer having certain items in your actionslots GearMenu can still be of use. By using the macro-bridge you get all the advantages of the combatQueue in a normal macro.

#### Add Item to CombatQueue

```
/run GM_AddToCombatQueue(itemId, enchantId, runeAbilityId, slotId)
```

Example - Equip Hand of Justice into the lower trinket slot

```
/run GM_AddToCombatQueue(233734, 0, 0, 11)
```

**Note:** The enchantId is optional. If you don't have multiple items with different enchantIds in your inventory, set it to 0.

**Note:** Season of Discovery requires the runeAbilityId to be set. This affects
Classic Era as well. Just set it to 0 if you don't have a runeAbilityId or you don't care about the rune (usually the case if you don't have multiple items with different runes).

**Note:** It is not recommended using this for weapons because addons cannot switch weapons during combat (GearMenu will put the item into the combatQueue). With a normal weaponswitch macro however this is still possible.

#### Clear Slot From CombatQueue

`/run GM_RemoveFromCombatQueue(slotId)`

##### Finding itemId

Finding the id of a certain item is easiest with websites such as [wowhead](https://classic.wowhead.com/ "").

##### Finding slotId

For finding the correct slotId refer to the image below. Only InventorySlotIds are valid targets for GearMenu

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_interface_slots.png)

## Configurability

GearMenu is configurable. Don't need a certain slot? You can hide it.

To show the configuration screen use `/rggm opt` while in-game and `/rggm` for an overview of options or check the standard Blizzard addon options.

### Creating a GearBar

With the latest release it is possible to create multiple GearBars that can act independently of each other.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_create_gearbar.gif)

### Configure a GearBar

Each GearBar has some configurations that can be done individually for each GearBar. This includes various sizes of the GearBar, its locked or unlocked state and what GearSlots are configured for the GearBar.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_configure_gearslots.gif)

### Individual GearBar Configuration

#### Hide/Show Cooldowns

Whether cooldowns should be shown or hidden can be configured individually for each GearBar.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_options_cooldowns.gif)

#### Hide/Show Keybindings

Whether keybindings should be shown or hidden can be configured individually for each GearBar.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_options_keybindings.gif)

#### Lock/Unlock Window

Whether a GearBar should be freely movable or be locked in place can be configured individually for each GearBar.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_options_lock_window.gif)

#### GearSlot Size

Every GearBar can have a different size for its GearSlots. You could, for example, have a GearBar with very big trinkets and another with smaller slots for less important items.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_options_gearslot_size.gif)

#### ChangeMenu Size

The size of the ChangeMenu can be configured independently of the GearSlot size.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_options_changemenu_size.gif)

#### Orientation

Each GearBar can lay out its GearSlots either horizontally or vertically. This makes it possible to place a vertical bar along the side of your screen while keeping another bar horizontal at the bottom.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_orientation_support.png)

When switching the orientation, you can also choose the direction in which the ChangeMenu opens relative to the hovered GearSlot. Horizontal GearBars open the ChangeMenu up or down, while vertical GearBars open it to the left or right so it does not overlap neighboring slots.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_vertical_and_horizontal_gearbar.png)

### General Configuration

#### Tooltips

GearMenu can show item tooltips when hovering items in its slots and change menus. Tooltips can be turned off entirely, or set to a simple mode that only displays the item name instead of the full tooltip.

#### FastPress Support

Enable whether an item in a Gearslot should be used when the player presses the key down (keydown) or only after the key is released (keyup).

### Filter Items by Quality

Not interested in seeing items with a quality level below a certain level? Filter them out and only items that meet your set level will be considered to be displayed in GearMenu.

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_options_filter_item_quality.gif)

#### Themes

GearMenu supports two different themes for its UI elements. By default, the custom theme will be used.

##### Custom

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_theme_custom.jpg)

##### Classic

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_theme_classic.jpg)

### TrinketMenu Configuration

TrinketMenu supports the following configuration features.

- Enabling/Disabling TrinketMenu completely
- Lock/Unlock the TrinketMenu
- Show or Hide trinket cooldowns
- Configure the number of columns of the TrinketMenu
- Adapt size of the TrinketMenu

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_trinketmenu_configuration.gif)

### Profiles

GearMenu lets you save your entire configuration as named profiles, so you can switch between different setups or carry your settings to another character. Profiles are managed under the **Profiles** tab of the configuration interface (`/rggm opt`).

![](https://raw.githubusercontent.com/RagedUnicorn/wow-gearmenu-meta/master/assets/gm_profile_configuration.png)

A profile captures your full GearMenu setup – all of your GearBars (their GearSlots, sizes, orientation, lock state and on-screen position), your QuickChange rules, the TrinketMenu settings, the selected theme and the general options.

- **Save current as...**: Snapshots your current configuration into a new named profile (or overwrites an existing one of the same name).
- **Apply**: Loads the selected profile, applies its settings and reloads the UI.
- **Rename**: Renames the selected profile.
- **Delete**: Removes the selected profile.

#### Sharing Profiles (Export / Import)

Profiles can be shared as portable strings, making it easy to copy a setup between characters or hand it to another player.

- **Export**: Generates a copy-pasteable profile string for the selected profile in the *Profile String* field.
- **Import**: Paste a profile string into the field and import it as a new profile. Imported strings are validated, so an invalid, corrupted, or non-GearMenu string is rejected without changing any of your settings.

> Note: Profiles are stored per character. Use export/import to move a profile to another character.

## FAQ

#### I get a red error (Lua Error) on my screen. What is this?

This is what we call a Lua error, and it usually happens because of an oversight or error by the developer (in this case me). Take a screenshot off the error and create a GitHub Issue with it, and I will see if I can resolve it. It also helps if you can add any additional information of what you were doing at the time and what other addons you have active. Additionally, if you are able to reproduce the error make sure to check if it still happens if you disable all others addons.

#### A certain item is not showing up when I hover a slot. Why is that?

GearMenu by default filters out items that are below uncommon (green) quality. This can be changed in the addon configuration settings in the option "Filter Item Quality".

#### GearMenu failed to switch my item. What happened?

There are certain limitations that make it harder to switch an item even if the player is out of combat. One such example is that WoW prevents switching items while the player is casting a spell. GearMenu detects this and changes the item as soon as there is a pause between two spells or if a spell was cancelled. Just keep this in mind if you absolutely need the item switch to happen as soon as possible. Another factor can be a loss of control effect such as sap, iceblock and similar effects. In such circumstances it is not possible to switch an item. GearMenu is aware of such effects on the player and will switch the item as soon as possible.

If you still think you found an issue where GearMenu doesn't switch items as expected feel free to create an [issue](#Issues).


#### Why can't I switch Weapons during Combat?

This is a limitation that Blizzard puts on addons. It is not currently possible to switch to an arbitrary weapon while in combat. It is however possible to create weaponswitch macros because it is already known from which weapon to what weapon the player wants to switch. While it is not ideal, to work around this issue GearMenu puts weapons in the CombatQueue if a weaponswitch is done while the player is in combat. If he is not in combat the switch will happen immediately. This might be improved in a future release if there is a better workaround possible.

> Note: It is also possible to switch a weapon by dragging and dropping the weapon in the standard Blizzard interfaces. This however is in no way connected to GearMenu

#### Why can't I create an Itemset?

This addon does not have the intention on supporting the functionality of switching between a PVE and a PVP set (or any other set). Its intention is to assist the player in switching single items fast and possibly during combat. It does not try to be the next Outfitter addon.

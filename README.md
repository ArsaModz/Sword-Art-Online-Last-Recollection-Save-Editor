# Sword Art Online: Last Recollection Save Editor (PS4/PC)
A save editor for *Sword Art Online: Last Recollection* on PS4 and PC, built in C# and WPF (.NET 4.7.2). Edit player resources, manage your full inventory, and fine-tune individual item stats across both platforms.

## 🚀 Key Features

### 📂 Platform Support
* **PS4 & PC:** Supports both `ue4savegame.ps4.sav` (PS4) and `ManualSave###.sav` (PC) save files.
* **Safety First:** Always keep a backup of your original save file before making any changes.

### 📈 General Stats (Tab 1)
Edit your core player resources:
* **Cash:** Set your in-game currency to any value, with a one-click MAX button.
* **Skill Points:** Adjust your available skill points (0–1000), with a one-click MAX button.
* **Play Time:** Set hours, minutes, and seconds freely, with a one-click RESET button.

### 🎒 Inventory Editor (Tab 2)
Manage your full inventory with a searchable, filterable item database:
* **View & Edit:** Browse all inventory slots in a DataGrid showing each item's name, type, category, and amount. Edit item and quantity inline.
* **Search & Filter:** Filter items by name or ID and toggle empty slot visibility.
* **Item Management:** Add items via a searchable dialog (filter by type or search by name/ID), or delete individual entries.
* **Bulk Add:** Instantly populate your inventory with all Weapons, Armors, Accessories, Consumables, or Materials in one click.
* **Bulk Modifiers:** Max or clear all item stats across your entire inventory at once, set skills on all items simultaneously, or max all Consumable and Material quantities.

#### Selected Item Stats Panel
When you select an item, a dedicated panel lets you fine-tune every stat on that item:

* **Skills:** Assign Skill 1 and Skill 2 from a searchable dropdown, or use **Set All Skills** to apply a skill pair to every item at once.
* **Core Attributes:** Max HP (×100), Max MP, Max SP, STR, VIT, DEX, AGL, INT, LUC, CHR.
* **Combat Stats:** Damage, Attack, Defense, EVD, Critical, Combat Fidelity.
* **Sacred Arts:** SA Damage, SA ATK, SA DEF, SA EVD, SA ACC, Special Effect ACC.
* **Modifiers & Cuts:** D-Cut, D-Cut Rate, Crit Resistance, Force, Heat, Internal, F/H/I (×2).
* **Resistances:** All Res, Dark Res, Poison Res, Paralysis Res, Stun Res, Mobility Res, Ability Down Res, Soul Res, Physical Res, Bleed Res.
* **Max Stats / Clear Stats** buttons apply to the currently selected item.

### 🔄 Converter (Tab 3)
Rename save files between platforms without modifying any save data:
* **PS4 → PC:** Renames `ue4savegame.ps4.sav` → `ManualSave000.sav` (slot 000–015 selectable).
* **PC → PS4:** Renames `ManualSave###.sav` → `ue4savegame.ps4.sav`.
* The renamed copy is saved alongside the original — your source file is never touched.

## 📝 How to Use
1. **Open:** Select your PS4 or PC save file.
2. **Edit:** Use the **General** tab to adjust resources, or the **Inventory** tab to manage items and their stats.
3. **Save:** Click **Save Changes** to write your edits back to the file.

---

## 🙏 Credits
* **[a_busy_man](https://fearlessrevolution.com/viewtopic.php?t=25913)** — Cheat table that helped map out the save file structure.

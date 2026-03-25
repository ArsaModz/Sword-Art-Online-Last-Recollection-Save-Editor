# SAO: Last Recollection Save Editor (PS4/PC)

A save editor for *Sword Art Online: Last Recollection*, developed with Python and PyQt6. Supports precise modification of inventory, per-item stats, skill assignments, and core player progression values directly within GVAS-format save files.

## 🚀 Key Features

### 🗡 Inventory Management
* **Item Slots:** View and edit up to 2,000 item slots across the full inventory.
* **Weapon & Skill Database:** Built-in CSV-backed lookup resolves item and skill names automatically.
* **Skill Assignment:** Set up to two skills per item directly from a searchable list.
* **Quantity Control:** Adjust item stack amounts per slot.

### 📊 Per-Item Stat Editing
Full control over every equippable stat on a per-slot basis:
* **Combat Stats:** Attack, Defense, Damage, Sacred Arts ATK/DEF, and more.
* **Resistances:** All elemental and status resistances (Poison, Bleed, Stun, etc.).
* **Attributes:** STR, VIT, DEX, AGL, INT, MND, CHR.
* **Misc:** EVD, Critical, D-Cut, HP/MP/SP bonuses, and others.

### 👤 Player Progression
* **Col:** Edit your in-game currency directly.
* **Skill Points:** Modify accumulated skill points.
* **Playtime:** Adjust the recorded play time.

## 🛠 Tech Stack
* **Language:** Python 3.x
* **GUI Framework:** PyQt6
* **Save Format:** GVAS binary parsing with CityHash64 hash recomputation for save integrity.
* **Data:** CSV databases for weapon and skill name resolution.

## 📝 How to Use
1. **Load:** Open your decrypted save file.
2. **Edit Stats:** Adjust Col, skill points, or playtime from the player tab.
3. **Manage Inventory:** Browse, search, and edit item slots and their stats.
4. **Save:** Write changes back to the file — hashes are recomputed automatically.

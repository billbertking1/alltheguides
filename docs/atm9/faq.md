---
title: ATM9 FAQ
description: ATM9 Frequently Asked Questions
authors: 
---

# FAQ

**All The Mods 9** Frequently Asked Questions

---

??? Question "Why can't I use modular router and watering can?"
    By default, **Mystical Agriculture** does not allow fake players to automate watering cans. If you dislike this change, it can be changed within `config/mysticalagriculture-common.toml` > `fakePlayerWatering = true`.

??? Question "Why is flight disabled?"
    Flight is disabled in certain dimensions (**The Other**, **Blue Skies**, and **Twilight Forest**), to add more difficulty towards progression. If you dislike this change, it can be disabled in `worldName/serverconfig/noflyzone.snbt`

??? Question "Why isn't '`insert name`' mod in ATM9 yet?"
    ATM packs does not literally contain "All The Mods". Our main focus is having mods that's not: 1) buggy, 2) ruins performance or progression. If a mod supports Minecraft version **1.20.1**, and **Forge** (Not NeoForge), you may make a [suggestion](https://github.com/AllTheMods/ATM-9/issues/1).
	
??? Question "Do I need to chunkload all the chunks my Chunk Destroyer is going to mine?"
    You do *not* need to load chunks you're mining. You only need to chunkload the chunk the **Chunk Destroyer** is in.

??? Question "I have my chunks force loaded, but they don't run when I'm logged off."
    1. Press ++m++ to open the map.
    2. Press ++ctrl+s++ to open the server settings (requires OP).
    3. Change `Forceloading Mode` to `always`.
	
??? Question "How do I remove enchants from a book/weapon?"
    - Drop an anvil onto **Obsidian** with the enchanted book/weapon along with **Books** for each separate enchantment (EX: You have a book with 3 different enchants, you'd need 3 books to split those enchants). 
	- Enchant the anvil with **Splitting** (Only splits books/weapons with 1 enchant) or **Obliteration** (Splits any number of enchants)
    - Use the **Enchantment Extractor** from Industrial Foregoing. Provide it with **Books** and **Power**, and it will extract each enchantment on all enchanted items/books to singular books. It can also be configured to push extracted enchantments into the **Enchantment Library** from Apotheosis.

??? Question "What's the little 3D cube next to my crosshair?"
	It's from Quark, the default keybind to toggle it is ++k++.

??? Question "How do I find '`insert name`' biome?"
    **Nature's Compass** is a really nice tool to find any and all biomes in the modpack. Craft it, right click with it in your hand, and you can run the search for any biome you are looking for (such as the Deep Dark).
<p align="center"><img src="https://i.imgur.com/eI9EIFJ.png"></p>

This repository contains a simple HTML page that generates a random magic item, weapon, or armor from a predefined list when you click a button. The project is built using **HTML**, **CSS**, and **JavaScript**. It includes a collection of **290 magic items** created for use with the 2014 rules for 5e.

---

## Features
- **Random Item Generation**: Click a button to generate a random magic item.
- **Customizable**: Easily add, edit, or remove items in the predefined list.
- **Lightweight**: No dependencies or external libraries—just HTML, CSS, and JavaScript.

---

## Usage

### How to Run
1. Download or clone the repository.
2. Open `index.html` in any web browser.
3. Click the button to generate a random magic item!

---

## Customization

You can edit the list of magic items to include your own creations. Here's how:

1. Open the `index.html` file in any text editor.
2. Scroll down to the `<script>` section where the `const magicItems` array is defined.
3. Add new items to the list using the following format:
   ```javascript
   { name: "Item Name", rarity: "Rare", attunement: "Yes/No", effect: "What does it do?" },
   ```
4. Save the file and open `index.html` in your browser to see your changes.

### Example
Here’s how a sample item looks in the array:
```javascript
{ name: "Flame Tongue Sword", rarity: "Rare", attunement: "Yes", effect: "Grants the ability to ignite the blade and deal fire damage." },
```

### Important Tips
- Ensure there is a **comma (`,`)** after each item, except for the last item in the list.
- The items are formatted for the 2014 5e ruleset. Compatibility with new rules may vary. Use at your own discretion.

---

## License
This project is shared under the **MIT License**. Feel free to modify, share, or use it in your own projects.

---

## Notes from Emerald_Void
The magic items included were created with the 2014 rules for D&D 5e in mind. Compatibility with newer rulesets has not been verified. Please use them as-is or adapt them to your campaign as needed. 

Enjoy creating and exploring magical treasures in your adventures! 🪄

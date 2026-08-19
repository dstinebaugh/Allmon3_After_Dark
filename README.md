# Allmon3 Custom Dark Themes

A small collection of dark themes for **Allmon3** (AllStarLink).

These are pure CSS drop-in replacements for `/etc/allmon3/custom.css`.

---

## Themes Included

| File | Description |
|------|-------------|
| `allmon3-after-dark-custom.css` | Black / dark-grey base with **red neon** accents for those long nights |
| `allmon3-carnage-node.css` | Black / dark-grey with **deep purple** neon node headers + **lime** Idle bar. Inspired by One Punch Man's Carnage Kabuto (personal fav) |
| `allmon3-murica.css` | The name should say nuff! **red** **white** and **blue** node titles (American flag inspired) |

All themes keep **active transmit / keyed states in red** for clear operational awareness.

---

## Installation

1. SSH into your Allmon3 server.
2. Backup the current custom CSS (if any):
   ```bash
   sudo cp /etc/allmon3/custom.css /etc/allmon3/custom.css.bak
   ```
3. Copy the theme you want:
   ```bash
   sudo cp allmon3-carnage-node.css /etc/allmon3/custom.css
   # or
   sudo cp allmon3-murica.css /etc/allmon3/custom.css
   # or
   sudo cp allmon3-after-dark-custom.css /etc/allmon3/custom.css
   ```
4. Restart Allmon3 (or just hard-refresh your browser):
   ```bash
   sudo systemctl restart allmon3
   ```
5. Hard-refresh the browser (`Ctrl+Shift+R` / `Cmd+Shift+R` / `Ctrl+f5`).

That’s it.

---

## Notes

- These themes were built and tested against Allmon3 with Bootstrap 5.3.
- Tooltips, modals, dropdowns, and action buttons are styled for dark readability. if I missed any LET ME KNOW THE ELEMENT NAME and I'll get it fixed!
- Feel free to edit the CSS variables at the top of each file to tweak colors.

---

73

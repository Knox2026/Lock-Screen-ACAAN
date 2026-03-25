# Lock Screen ACAAN

A high-fidelity, stealth utility designed for modern performance. This Progressive Web App (PWA) mimics a standard smartphone lock screen (iOS, Android, or Samsung) to provide covert data for Any Card At Any Number (ACAAN) effects.

## 🚀 Key Features

* **Innocent Mode:** Displays the actual system time and date upon launch and after reset.
* **Voice-Triggered Logic:** Listens for a customizable "Trigger Word" (Default: *Focus*) to activate calculations.
* **Multi-Stack Support:** Pre-loaded with 6 professional stacks:
    * Redford
    * Mnemonica
    * Aronson
    * Memorandum
    * Particle System
    * Si Stebbins (CHaSeD)
* **Shortest Path Calculation:** Automatically calculates the most efficient cut (Top-to-Bottom vs. Bottom-to-Top).
* **Screen Wake Lock:** Prevents the display from dimming or sleeping during a performance.
* **Verification Crib:** Uses the "Date Line" to verify the resulting bottom card of the deck.

---

## 🛠 Operation & Gestures

| Gesture | Action | Performance Context |
| :--- | :--- | :--- |
| **Single Tap** | Activate Mic + Wake Lock | "Prime" the app when setting the phone down. |
| **Double Tap** | Clean Exit | Instantly reset to actual real time/date. |
| **Long Press** | Config Menu | Hidden access to stacks, UI styles, and offsets. |

---

## 📋 Calculation Logic (The "Crib")

Once a calculation is triggered, the clock updates to show your instructions:

* **Minutes (01–26):** The number of cards to be shifted.
* **AM:** Cut cards from the **TOP** of the deck to the bottom.
* **PM:** Cut cards from the **BOTTOM** of the deck to the top.
* **Shift 0:** Displayed as `[Real Hour]:00 AM` and `Sunday [Month] 24` to indicate the card is already at the target position.

### Date Line Verification (Bottom Card)
The Date identifies the card that should be at the **Bottom** of the deck after the cut is completed:
* **Monday:** Clubs (♣) 
* **Tuesday:** Hearts (♥)
* **Wednesday:** Spades (♠) 
* **Thursday:** Diamonds (♦)
* **Number:** Ace=1, Jack=11, Queen=12, King=13.

---

## 🔧 Installation & Updates

1.  **Host on GitHub Pages:** Upload `index.html`, `manifest.json`, and `sw.js` to a repository.
2.  **Add to Home Screen:** Open the URL in Safari (iOS) or Chrome (Android) and select "Add to Home Screen" to run as a standalone PWA.
3.  **Updating:**
    * Update the `CACHE_NAME` in `sw.js` to force the phone to pull the latest version.
    * Ensure the manifest link in `index.html` matches the version (e.g., `href="manifest.json?v=8.9"`).
    * Use the **"Check for Update"** button within the Config Menu to refresh the cache.

---

## 📝 Version History
* **v8.9:** Finalized documentation and gesture summary table.
* **v8.7:** Integrated Screen Wake Lock API.
* **v8.6:** Added "Innocent Mode" (Real-time clock integration).
* **v8.5:** Certified accuracy audit of all 6 stacks.

---

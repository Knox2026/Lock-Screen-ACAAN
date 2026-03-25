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
* **Shift 0:** Displayed as `[Real Hour]:00 AM`. 

### Date Line Verification (Bottom Card)
The Date identifies the card that should be at the **Bottom** of the deck after the cut is completed:
* **Monday:** Clubs (♣) 
* **Tuesday:** Hearts (♥)
* **Wednesday:** Spades (♠) 
* **Thursday:** Diamonds (♦)
* **Number:** Ace=1, Jack=11, Queen=12, King=13, and 2-10.
* The app will display `Sunday [Month] 24` to indicate the card is already at the target position.

---

## 🔧 Installation & Updates

**Add to Home Screen:** Open the URL in Safari (iOS) or Chrome (Android) and select "Add to Home Screen" to run as a standalone PWA.
**Updating:**
 * Use the **"Check for Update"** button within the Config Menu to refresh the cache.

---


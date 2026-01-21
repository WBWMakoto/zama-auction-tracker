# 🛡️ ZAMA Auction Tracker (DOM-based & Fully Automated)

<img width="1915" height="952" alt="image" src="https://github.com/user-attachments/assets/c2dcf83f-642c-4ed9-8206-68c7d8e13c68" />

> **⚠️ Current Status:** 🚧 **Pending Approval**
> This script is currently for internal/personal testing. I am waiting for confirmation from the **@zama** team to ensure this tool can be public shared.

A browser-based analytics tool for tracking the **$ZAMA Dutch Auction**. This script runs directly in your browser console and acts as an **"Auto-Pilot"** for your auction data—parsing the Live Feed and calculating insights automatically in real-time.



## ⚡ Why Use This? (The "Set & Forget" Experience)

* **🧘 Truly Hands-Free:** Just paste the code **ONCE**. The script automatically clicks the "Live Feed" tab, manages scrolling to fetch history, and keeps the data fresh.
* **🚫 No Manual Refreshing (No F5):** The tracker intelligently re-scans the screen every **60 seconds**. You don't need to reload the page or touch the keyboard.
* **📉 Real-time Valuation:** Watch the numbers update themselves as new bids come in.
    * **Auction FDV:** Instantly converts bid prices to Fully Diluted Valuation.
    * **Clearing Price:** Projects the cutoff price based on the current shielded value.
* **📊 Dynamic Visuals:**
    * **Smart Markers:** 💎 Expected / 🟢 Mean / 🔴 Median / ⚡ Cutoff.
    * **Velocity Indicators:** 🟢 Rising / 🔴 Falling momentum over time (1m, 1h, 12h).

## ⚙️ How to Use (3 Simple Steps)

1.  **Open Console:** Go to the ZAMA Auction page and press `F12` (or Right Click -> Inspect -> Console).
2.  **Paste & Enter:** Paste the source code into the console and hit `Enter`.
3.  **Sit Back & Relax:** That's it!
    * The script will verify the "Live Feed" tab is active.
    * It will auto-scroll to load necessary data.
    * It will print a beautiful dashboard that updates itself every minute.

---

### 💡 IMPORTANT: Keep It Running Smoothly
Since this tool is **100% automated**, modern browsers might try to "sleep" the tab to save battery if you switch away. To ensure the automation never stops:

* **Best Method:** Pull the ZAMA tab out into its **own separate window** and leave it visible on your screen.
* **Alternative:** Turn off "Memory Saver" or "Battery Saver" in your browser settings.

---

## 🛡️ Technical & Ethics

* **Zero API Spam:** This tool does **not** send hidden requests to the ZAMA backend. It strictly reads the HTML elements currently displayed on your screen (DOM Parsing).
* **Lightweight:** The automation triggers every 60 seconds, designed to be non-intrusive and safe for long-term monitoring.

## 📝 Disclaimer

**THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.**

* This is a community-built tool created by **[@WBW_Makoto](https://x.com/WBW_Makoto)** and is **not** officially affiliated with ZAMA.
* Use this tool at your own risk.
* The logic relies on the website's HTML structure. If ZAMA updates their UI, this script may need an update.



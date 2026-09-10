# Chimera Kites Training Environment

A dynamic, modular training environment for DCS World (Caucasus Theater) powered by the MOOSE framework. Built for dedicated squadrons and public multiplayer hosting, featuring on-demand Air-to-Air (A/A), Air-to-Ground (A/G), dynamic moving convoys, multi-tier SEAD/DEAD threats, and automatic range sanitization via the F10 radio menu.

---

## 🦅 Key Features

* **Modular Airspace Architecture:** 
  * **Western Corridor:** Dedicated to A/G gun runs, precision-guided munition (PGM) deliveries, moving convoys, and point-defense suppression.
  * **Eastern Sector:** Mountainous training ground for coordinated BVR air combat and multi-tier SEAD/DEAD joint strikes.
* **Smart AI Behavior:** Bandits and SAMs utilize robust holding orbits and tactical engagement rules to eliminate RTB-bugs and maintain active station.
* **Range Sanitization System:** Real-time cleanup functions purge dead static hulls, craters, and burning wrecks on demand to maximize performance and server stability.
* **On-Demand Tankers & AWACS:** Blue AWACS and dual-profile aerial refueling (Boom & Drogue) accessible live without cluttering the map at mission start.

---

## 🗺️ Operational Ranges

### 1. Air-to-Ground (A/G)
* **Kobuleti Airfield (Easy):** 
  * Unarmed trucks on runways (Gun, rocket, and CCIP practice).
  * Static armor on taxiways (T-55, BMPs for LGB/Maverick practice).
* **Highway Moving Convoy (Kvitiri ➔ Abkhazia):**
  * *Soft Convoy:* Unarmed logistics transports.
  * *Armed Convoy:* Escorted by mobile AAA (ZSU-23-4 Shilka) and SHORAD.
* **Ochamchira SHORAD:** High-threat short-range point defense (SA-15 Tor / SA-19 Tunguska).
* **East Dynamic SAM Sites (SEAD/DEAD):** Randomized placement across North, Central, and South ridges featuring 4 selectable threat tiers:
  * **Tier 1:** SA-3 Goa (Vintage conical radar)
  * **Tier 2:** SA-6 Gainful (Mobile radar SAM)
  * **Tier 3:** SA-11 Buk (Advanced multi-target)
  * **Tier 4 (Final Boss):** Integrated Air Defense complex protected by close-in Tor and Tunguska units.

### 2. Air-to-Air (A/A) Arena
* **Flight Sizes:** Selectable 1x (Single), 2x (Pair), 3x (Section), or 4x (Division).
* **Tiers:**
  * *Surprise:* Randomized threat generator.
  * *Tier 1 (Introductory):* MiG-29, Mirage 2000-5.
  * *Tier 2 (Advanced):* F-15C, Su-30.

## 🚀 Installation & Usage

1. Download the latest `.miz` release from the [Releases](../../releases) tab.
2. Place the file into your local missions folder:
   ```text
   C:\Users\<YourUser>\Saved Games\DCS\Missions\

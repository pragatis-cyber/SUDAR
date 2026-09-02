<img width="1416" height="952" alt="image" src="https://github.com/user-attachments/assets/2afad578-3597-4274-99a7-9b10575ce873" /># SUDAR
Sudar - Your Safer Way Home | It is a women's safety application for safe route suggestion — helping users choose paths that prioritize their safety over just the fastest route.

# Sudar - Safer Ways Around SRM Kattankulathur

**A route picked for the well-lit, well-walked way - not just the shortest one.**

Sudar is a women's safety web app built by **Team Fam.exe** for the Dominion hackathon. Instead of just showing the fastest route from A to B, Sudar scores every path on a campus network by *how safe* it feels to walk - and lets you choose the route that keeps you safest, not just quickest.

---

## ✨ Features

### 🗺️ Safe Route Suggestions
Enter a starting point and destination and Sudar computes two options side-by-side:
- **Safest route** - optimized for lighting, foot traffic, and low incident reports
- **Shortest route** - the standard fastest path

Each route shows distance, estimated walk time, and an overall safety score, so you can weigh a few extra minutes of walking against a meaningfully safer path.

### 📊 Safety Scoring Model
Every path segment is scored 0 - 100 using a weighted blend of:
- **Lighting**
- **Foot traffic / crowd density**
- **CCTV coverage**
- **Community incident reports**

The weighting isn't fixed - it shifts with **time of day** (lighting matters most at night, foot traffic matters most during the day), and the route score combines the average across the path with its *weakest single segment*, so one scary stretch can't hide behind an otherwise-good average.


### 📢 Community Safety Reports
Users can tap any spot on the map to flag it - lighting issues, low foot traffic, safety suggestions, maintenance needs, or general feedback. Reports:
- Are shown to everyone using the app
- Quietly lower that segment's safety score
- **Decay over time** (roughly two weeks) so a fresh report matters more than a stale one, and a single unconfirmed report fades faster than a corroborated one
- Are always **anonymous** - never linked to the reporter's name or account, even if they're signed in

### 🧭 Live Location & Map Tools
- "Use my location" to auto-select your nearest starting point
- Click-to-set location as a fallback when GPS isn't available
- Toggleable map layers: help points, community reports, and a safety heatmap

### ♿ Accessibility Mode
A wheelchair-accessible routing toggle that avoids narrow paths, falling back gracefully to the standard route when no accessible path exists.

### 🌐 Multilingual Support
Full interface available in **English, Tamil, and Hindi**.

### 🆘 Emergency Info
Quick access to emergency numbers (112 and the Women Helpline 181) built directly into the app, since Sudar itself doesn't contact emergency services.

### 🔐 Privacy-Minded Design
A lightweight sign-in personalizes the session (just a display name), but is deliberately kept separate from safety reporting - so who reported what stays unknown even to other signed-in users.

---

## ⚠️ Disclaimer
This is a **hackathon prototype** built for SRM Kattankulathur. Path data, lighting/CCTV/crowd values, and safety scores are illustrative placeholders for the demo - not verified real-world safety information. In a real emergency, always call **112** or the **Women Helpline 181**.

---

## 👥 Team Fam.exe
Built with care by a team of 3 for our first hackathon - Dominion.

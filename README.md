# Fusion Presets by Parker

A curated preset collection for the Fusion ecosystem, designed for users who want a clean, optimized, and experience-focused setup for streaming via Debrid services.

These presets prioritize **actual viewing experience over raw bitrate**, favoring formats like IMAX, high-quality encodes, and properly structured releases rather than simply the largest file available.

The goal is simple: in tested usage, the first result should consistently provide the best overall viewing experience.

⚠️Important: This setup is not anime-focused and not designed for anime use cases in any way.

---

# 📦 Fusion Presets (Filters)

### Installation

Import the main filter preset directly into Fusion Media Center:

```
https://imightbeparker.github.io/Fusion-Presets-Parker/presets/manifest.json
```

Then paste it into:

**Settings → Filters → Import Filters**

---

### What this includes

These filters are intentionally curated and trimmed to remove noise. They focus on:

- Resolution prioritization
- Visual quality tags (HDR, IMAX, etc.)
- Audio formats and quality
- Release quality indicators (WEB-DL, REMUX, BluRay, etc.)
- Clean prioritization logic for best-first results

This is not a maximal tag list — it is a **refined, opinionated system** built around real-world playback results.

If the first stream appears to be missing tags that lower-ranked streams have, note that those attributes are still accounted for in the AIO Streams configuration. However, some elements—such as file naming—are outside my control, and certain tags may not always display or behave consistently.

I’m open to any suggestions or improvements, especially regarding the AIO Streams formatter. For example, it currently lacks proper black-and-white detection, such as for Spider-Noir. 

Invite Link: https://discord.gg/KtEDvGSEC

Discussion: Fusion → Configs → Fusion Presets by Parker

---

# 🎬 AIOStreams Configuration

This configuration is tuned specifically for **Debrid-only users**, with a focus on English-language viewing and high consistency in playback quality.

### Installation

Download the provided AIOStreams configuration file from this repository and import it directly into the AIOStreams website/tool interface.

---

### Design philosophy

- Optimized for Debrid services only
- Prioritizes high-quality, properly tagged releases
- English-focused playback assumptions
- Structured to reduce low-quality or duplicate results

This setup may not be suitable for Torrent-based or mixed-source configurations.

---

# 🧩 AIOStreams Formatter

A separate formatter preset is included for users who only want improved formatting without the full configuration layer.

### Installation

Download the formatter preset file and import it into the AIOStreams formatter section on the official tool site.

---

# 🖼 AIOMetadata Configuration

A minimal, universal metadata configuration designed for simplicity and compatibility.

### Features

- Only essential and widely supported catalogs
- Clean metadata structure
- No excessive or redundant sources

Poster handling is intentionally external and handled via **BetterPosters**, allowing full customization without bloating metadata sources.

### Installation

Download the AIOMetadata configuration file and import it into the AIOMetadata tool interface.

---

## 🎨 Icon Packs (Recommended)

This icon pack is a nice visual enhancement created by **https://github.com/itsrenoria** and is recommended for use.

### How to use


```
https://raw.githubusercontent.com/itsrenoria/fusion-starter-kit/refs/heads/main/json/icon-packs/icon-packs-yodaluca23.json
```
Settings → Icon Packs → Add Icon Pack → Paste URL
Settings → Metadata → Community Rankings → Enable → Assign Icons 

---

# ⚠️ Important Notes

- These presets are **opinionated** and reflect personal preferences.
- They are designed specifically for **Debrid-based setups**.
- Not guaranteed to be optimal for all users or all regions.
- The ordering logic is tuned for “best-first playback experience”, not maximum file size or raw bitrate.

---

# 🙏 Credits

This project builds on ideas and structures from:

- BetterFormatter
    https://9mousaa.github.io/BetterFormatter/ 
- Fusion Widget Manager
    https://nobnobz.github.io/fusion-widget-manager/ 

All original work belongs to their respective creators. This repository is a **curated and simplified combination and refinement** of existing ideas, adapted for a more streamlined experience.

---

# 🎯 Summary

A unified preset collection for Fusion users who want:

- Cleaner filtering logic
- Better default playback outcomes
- Less clutter, more signal
- A Debrid-first optimized experience

Shared publicly as a personal configuration that consistently performed best in real-world use.

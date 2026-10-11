# Echoes of Astra — fan simulator

Fan-made, personal-use simulator for the Echoes of Astra TCG. Open the GitHub Pages site (or `index.html`) in a browser — desktop or phone, portrait or landscape.

## Features
- **Play vs AI**, **two players on one device**, and **online play** — one player hosts a room and shares a 6-character code, a link or a QR code; the other joins from any device.
- **Three visual styles** to choose from: *Orbital Crown* (imperial orbital chivalry, the default), *Neon Noir* (rain-soaked cyberpunk) and *Ashen Relic* (dark-fantasy gothic). Switch with **STYLE** on the main menu or in **Settings**. Preview a style directly with `?theme=crown`, `?theme=noir` or `?theme=relic`.
- **Drag cards from your hand onto the table** to play them (or onto your supply to put them into supply and draw), and **drag a unit onto a zone to attack** — tapping still opens the card details.
- Phone **landscape mode**; on iPhone/Android use *Add to Home Screen* for full-screen play without browser bars.
- Voiced cards (spells are voiced by a male or female Sovereign to match your portrait), pre-rendered music and synthesized sound effects; all 165 Imperion cards automated.

## Online play
Online matches connect the two browsers directly (WebRTC). The free PeerJS cloud server is only used to introduce the players. Both players must use the same version of the game. Some very strict networks (some corporate or school Wi-Fi) can block direct connections — mobile data usually works.

Echoes of Astra, its card names, rules and card images belong to Parhelion Studio. Card images are loaded from the publisher's site and are not stored in this repository.

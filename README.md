# Echoes of Astra — fan simulator

Fan-made, personal-use simulator for the Echoes of Astra TCG. Open the GitHub Pages site (or `index.html`) in a browser — desktop or phone, portrait or landscape.

## Features
- **Campaign**: five fronts (one per affinity) plus a final chapter. Each chapter is a run of four fights — two champions, an elite and a boss with their own powers. Pick a Banner deck, then grow it after every win with card bundles, Forge upgrades and treasures. Renown buys permanent Sovereign perks; chapters unlock Heroic mode, Trials (win-this-turn puzzles) and cosmetics (titles, card backs, portrait frames).
- **Play vs AI**, **two players on one device**, and **online play** — one player hosts a room and shares a 6-character code, a link or a QR code; the other joins from any device.
- **Deck sharing**: every deck has a short code, a link and a QR code; import decks from a code, a link (`#deck=…`) or a pasted card list.
- **Drag cards from your hand onto the table** to play them (or onto your supply to put them into supply and draw), and **drag a unit onto a zone to attack** — tapping still opens the card details.
- A clean match screen in the *Orbital Crown* style, with your supply shown as a row of crystals (ready, spent, floating and the Extend Supply socket).
- Phone **landscape mode**; on iPhone/Android use *Add to Home Screen* for full-screen play without browser bars.
- Character voice lines for units (spells, items and territories play sound effects), pre-rendered music and synthesized sound effects; all 165 Imperion cards automated.

## Online play
Online matches connect the two browsers directly (WebRTC). The free PeerJS cloud server is only used to introduce the players. Both players must use the same version of the game. Every move is checked against the rules on both devices, the shuffle seed is agreed fairly by both players (commit–reveal), and malformed or flooding messages are ignored. Some very strict networks (some corporate or school Wi-Fi) can block direct connections — mobile data usually works.

Echoes of Astra, its card names, rules and card images belong to Parhelion Studio. Card images are loaded from the publisher's site and are not stored in this repository.

# Hypixel Skyblock Auction Browser

A powerful and user-friendly application for browsing and filtering auctions in Hypixel Skyblock using Hypixel's Auction API.

## Features
Easily search and filter auctions to find exactly what you're looking for. The application allows you to:
- Fetch all active auctions from the Hypixel API.
- Apply various filters to refine your search.
- Search for auctions by a specific player using their IGN.

## Filters
The application currently has the following filters to modify:
- **Search** – Find specific items by item-name.
- **Ultimate Enchant Selector** – Filter auctions by specific ultimate enchantment.
- **Item Category Selector** – Filter auctions by item type.
- **Item Rarity Selector** – Filter auctions by item rarity.
- **Dungeon Stars Selector** – Show only items, with specific amount of dungeon-stars.
- **Max Price Specification** – Set a maximum price to narrow down auctions.
- **Fully Scrolled** – Filters for fully scrolled Wither Blades.
- **Only BIN's** – View only BIN

## How It Works
When launching the application for the first time, it will start empty. Press the **Fetch** button to retrieve the latest auctions from the Hypixel API. The fetched auctions, along with the last retrieval timestamp, are saved to a file. On subsequent launches, the application loads data from this file to avoid excessive requests to the Hypixel API. This helps prevent unnecessary API stress. *(More details: [Hypixel API Documentation](https://api.hypixel.net/#tag/SkyBlock/paths/~1v2~1skyblock~1auction/get))*

## Usage
- Scroll or search through all auctions.
- Double-click an auction to view its details, including the seller and in-game command to inspect the auction.

Enjoy a better auction browser with the Hypixel Skyblock Auction Browser!


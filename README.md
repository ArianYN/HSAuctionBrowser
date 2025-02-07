# Hypixel Skyblock Auction Browser
An application to easily browse and filter Auctions for Hypixel Skyblock using Hypixels Auction API

# Features
With this application, you can fetch all auctions from the Hypixel API, and find exactly the item you are looking for using various filters.
You can also search for auctions from a specific Player, by their IGN

# Filters
These are the filters that currently exist for the application:
- Ultimate Enchant Selector
- Item Category Selector
- Item Rarity Selector
- Dungeon Stars Selector
- Max Price Specification
- Fully Scrolled (Of course only works with to Wither Blades.)
- Only BIN's

# Info

When starting the application for the first time, it will be empty. You will need to press "Fetch" to fetch all auctions from their API.
This action saves the Auctions and "Last-Fetch" time to a file. Next time the application is opened, it will read from this file to start with.
This is done to prevent the application from stressing Hypixels API by too many requests (https://api.hypixel.net/#tag/SkyBlock/paths/~1v2~1skyblock~1auction/get)

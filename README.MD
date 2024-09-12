
# iTEM

[![Discord](https://img.shields.io/discord/932106421338779709?label=discord&logo=Discord&logoColor=FFFFFF%22)](https://discord.gg/s6u5P54pFy)
---

__What is iTEM?__

iTEM is an open source, community-led effort to track every single item in Hypixel Skyblock.

By contributing to the effort, you earn "contributions" (because you contributed), and using the contributions you can search the iTEM database for (currently) exotic armour sets, applied pet skins, and unapplied pet skins. In the future, you will be able to search for any item with any attribute you want.

iTEM uses this data to be able to provide "active dupe checking", item ownership history, quick access to item nbt, hypixel searches, item statistics/rarity, and more to come.

It also provides handy in-game features, such as lobby scanning for exotics, exotic labelling (eg fairy/spooky/exotic/glitched), copying item uuid to clipboard, dupe-checking via a hotkey, and armour rarity annotations (how many there are in the game).

At the moment, it takes 12 hours for any item/inventory update to be reflected in the iTEM database. We have over 110 million items tracked, and almost 15 million players known about.

We currently aren't advertising as we want to build up the utility and add more publically accessible options (eg https://tem.cx is being worked on) and uses for the database, but you can join while we're in beta and help to contribute.

[Join the Discord!](https://discord.gg/s6u5P54pFy)

---
## How to build?

### Protoc Files

`protoc -I . --java_out annotate_code:src/main/java/ clientMessages.proto`

`protoc -I . --java_out annotate_code:src/main/java/ serverMessages.proto`

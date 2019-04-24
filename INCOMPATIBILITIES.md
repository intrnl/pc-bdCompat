# Notes on incompatibiltiies

- Regarding monkey patching
  - Some plugins, especially those that uses their own plugin library, patches Discord's functions, and if it's not done through BD's API for monkey patching then it can lead to breakages.

- Plugins that enhances BetterDiscord's emotes feature
  - Affects plugins like EmoteSearch
  - No, they don't work. Why? Go figure.

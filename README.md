# Projects:
This contains all releases I've ever made and am maintaining. The ones I still have anyway.
<br>They're all in a pretty neat format, so you can effectively download anything with ease if you know your way around the system.

# Versioning:
Ever since 1.19.3, Mojang's changed how their updates work. A side effect of this is that: If you now use a version that wasn't designed for the Minecraft release you're on, [you're going to have issues](https://web.archive.org/web/20221025032759/https://help.minecraft.net/hc/en-us/articles/9971900758413).
<br>To combat this, I've devised a Version Numbering Scheme that aims to let you know which version was built for which Release.
## How it works:
It's quite simple: **Look at the letter in the version number**. That shows you the Minecraft Release it was built for.
- `-` means it's for the base version:
  - 20-x => for 1.20, 21-x => for 1.21, ...
- `a` = `.1`, `b` = `.2`, and so on:
  - 20`c`x => for 1.20`.3`, 20`b`x => for 1.20`.2`, ...
  - There's no way we'd reach past update `.26`, which is `z` for this numbering scheme. (Highest is `.11` so far)
- **Note that if the Release itself only contains bugfixes, roll back a letter!**
  - 20`d`x would've been designed for 1.20`.4`, but since that update only has some bugfixes, 20`c`x is built for 1.20.3 and 1.20.4 as well.
- For Minecraft 26 and above (I like to call it 1.26), [because Mojang changed their numbering system](https://web.archive.org/web/20260131133943/https://www.minecraft.net/en-us/article/minecraft-new-version-numbering-system), I'm adding a dot that's meant to separate the Minecraft Release it's meant to be for and the version number.
  - So 26`a`.x => Minecraft 26`.1`, but 26`a1`.x => Minecraft 26`.1.1` (the 0 in the first example isn't added)

# License:
By downloading and using my packs, you agree to the license stated [here](https://thediamondplayables.github.io/projects/license.html).

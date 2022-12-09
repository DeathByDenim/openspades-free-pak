# Usage

Pak files are just zip file. To create a pak file from these assets, run:

```
zip -r pak001-Free.pak Gfx/ License/ Models/ Sounds/
```

Then place the "pak001-Free.pak" in the same directory as the other pak files that come with OpenSpades. For example, /usr/share/openspades/Resources/. This will then overrule any assets in "pak000-Nonfree.pak". You could even delete that one.

Almost all assets in this pak are CC0 with a few exceptions. See the credits in the License subdirectory.

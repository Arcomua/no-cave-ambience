![banner that shows a disabled speaker icon with Minecraft cave background](https://i.imgur.com/Fdy0WmZ.png)

# No Cave Ambience

A simple resource pack to get rid of creepy cave ambience sounds.

## How?

Replace sounds with empty oggs created using `ffmpeg -f lavfi -i anullsrc=r=44100:cl=mono -t 0.000001 -c:a libvorbis cave.ogg`

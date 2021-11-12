# bili

**bili is just a bilibili video download script for Termux.**

### How

Move bili file into your preferred bin folder.

### Setup example for Termux
```bash
pkg up -y && pkg in -y git && git clone https://github.com/RellikJaeger/bili && cd bili && pkg up -y && pkg in -y python ffmpeg && pip install youtube-dl && chmod +x bili && mv bili ~/../usr/bin
```
### Usage
```bash
bili https://b23.tv/Al8T0j
```
### Output

/sdcard/Download/$filename.mp4

PS: Need to update some parts for general purpose.

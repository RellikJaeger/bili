# bili
**bili is just a bilibili video download script for Termux.**  
### Tip
- Move bili file into your preferred bin folder.  
### Setup example for Termux  
- Copy and paste this into Termux.
```bash
pkg up -y && pkg in -y git python ffmpeg && python -m pip install --upgrade pip && pip install youtube-dl && git clone https://github.com/RellikJaeger/bili && cd bili && chmod +x bili && mv bili ~/../usr/bin && cd .. && rm -rf bili
```
### Usage example
- Copy and paste this into Termux.
```bash
bili https://b23.tv/Al8T0j
```
### Output file path
- You can find your downloaded video file in the internal storage "Download" folder.  
#### Example paths:
| "/sdcard/Download/Video Name-VideoID.mp4"             |
| --- |
| "/storage/emulated/0/Download/Video Name-VideoID.mp4" |
> PS: Need to update some parts for general purpose.

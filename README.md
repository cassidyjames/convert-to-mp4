# convert-to-mp4
Convert a video to MP4 from inside of Files. Designed for [elementary OS](https://elementary.io).

## Prereqs

```bash
sudo apt install ffmpeg
```

## Installing

Copy `convert-to-mp4` to somewhere in your path and set ownership/permissions, i.e.

```bash
sudo cp convert-to-mp4 /usr/local/bin/
sudo chown root:root /usr/local/bin/convert-to-mp4
sudo chmod 755 /usr/local/bin/convert-to-mp4
```

Copy the contract into a contractor directory and set ownership/permissions, i.e.

```bash
sudo cp convert-to-mp4.contract /usr/share/contractor/
sudo chown root:root /usr/share/contractor/convert-to-mp4.contract
sudo chmod 644 /usr/share/contractor/convert-to-mp4.contract
```

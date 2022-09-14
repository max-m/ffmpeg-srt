# ffmpeg with SRT support
Custom build with SRT protocol support enabled

## Add Repo:
```
# Add the public key
wget -O ffmpeg-srt.key https://max-m.github.io/ffmpeg-srt/public.key
sudo apt-key add ffmpeg-srt.key
rm ffmpeg-srt.key

# Make sure that apt-add-repository is available
apt-get install software-properties-common

# Add the repository
sudo apt-add-repository --update 'deb [arch=amd64] https://max-m.github.io/ffmpeg-srt/repo focal main'
```

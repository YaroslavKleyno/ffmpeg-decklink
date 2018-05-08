# ffmpeg-decklink


1) Determine devices using command: 

ffmpeg -f decklink -list_devices 1 -i dummy
ffmpeg -i rtmp://path/to/stream -f decklink -pix_fmt uyvy422 "DeckLink SDI"

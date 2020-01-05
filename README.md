# blaze

```
Options
  -s / --save
    End the recording (Warning, kills all instances of ffmpeg)

  -h / --help
    Display what you're reading right now

  -c / --confirm
    Don't ask if the user is ready to record

  -p / --preset   []
    Save to and load from preset <x>

  -b / --bitrate  []
    Force bitrate  (in MB)

  -r / --rate     []
    Force framerate

  -m / --method   []
    Force method   (slop, display)

  -d / --display  []
    Force display  (Doesn't require -m)

  -S / --slop
    Options to use for slop
    Requires slop's options to be quoted


[] = Option requires a value

Anything after these will be the output file (optional)

Variables
  BLAZE_DIR
    Location to save the video
    Default: '$HOME/opt/x/recs'

  BLAZE_FILE
    Name of the saved video
    Default: 'blaze-$(date '+%Y-%m-%d_%H-%M-%S').mp4'

  BLAZE_SLOP
    Options to use for slop
    Default: None
```

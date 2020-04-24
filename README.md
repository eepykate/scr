# blaze

Personal recording script, lots of weird deps, don't use

```
Options
  -s / --save        End the recording
  -h / --help        Display what you're reading right now
  -d / --deps        Print dependencies
  -c / --confirm     Don't ask if the user is ready to record
  -p / --preset   [] Save to and load from preset <x>
  -r / --rate     [] Force framerate
  -b / --bitrate  [] Force bitrate  (in MB)
  -m / --method   [] Force method   (slop, display)
  -D / --display  [] Force display  (Doesn't require -m)
  -n / --nvenc       Force disable NVENC
  -S / --slop        Options to use for slop (Needs to be quoted)
  -a / --audio       Record desktop audio

To select an area, install 'slop',
to select a display, install 'pockata/mmutils'

[] = Option requires a value

Final argument not starting with `-` will be output file

Variables
  BLAZE_DIR    Location to save the video
    Default:     Current directory

  BLAZE_FILE   Name of the saved video
    Default:     'blaze-$(date '+%Y-%m-%d_%H-%M-%S').mp4'

  BLAZE_SLOP   Options to use for slop
    Default:     None
```

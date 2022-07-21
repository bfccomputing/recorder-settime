# recorder-settime
This writes out the RECSET.txt file needed by some pocket digital voice recorders.

## Usage
Mount your recorder as your user.

./settime /path/to/RECSET.txt

Unmount your recorder "safely".
Remove cable and turn on.
Do a test recording.
Plug it back in and verify the dates are what you expect.

Edit the script if you want to change the time offset from UTC.  There doesn't seem to be any timezone support, so you can either have the filenames' timestamps correct in local time or the file dates correct in local time, but not both.  I chose to keep it in UTC since there's no support for Daylight Saving Time.  Yet another reason DST is stupid.

## Support
Open an issue if you see a problem.  Best effort.  Probably low effort.

## Roadmap
Maybe set the other options.  The bitrates in the advice comments don't even say what the WAV sampling rate is.  Make a map.

## Contributing
Feel free to make pull requests for features or fixes.

## Authors and acknowledgment
Bill McGonigle <bill-settime@bfccomputing.com>        

## License
WTFPL v2

## Tested Devices
[v13 64GB Voice Recorder, Telele Digital Audio Recorder](https://amzn.to/3IWNP2g)

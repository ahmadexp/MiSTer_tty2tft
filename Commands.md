| Commands                | Meaning       |
| ----------------------- |-------------- |
| CMDCLS                  | Black out screen |
| CMDCRED                 | Fill screen red (just for testing) |
| CMDDON                  | Turn on screen (ILI9341 only) |
| CMDDOFF                 | Turn off screen (ILI9341 only) |
| CMDDINVON               | Invert screen on (ILI9341 only) |
| CMDDINVOFF              | Invert screen off (ILI9341 only) |
| CMDRESET                | Restart ESP |
| CMDSNAM                 | Show picture's name |
| CMDROT,PARAM            | Rotate screen (0=none,1=90°,2=180°,1=90°,3=270°) |
| CMDDUPD                 | Refresh screen |
| CMDDELETE               | Delete actual picture/video from SD |
| CMDUPLOAD,URL           | Upload file from <URL> |
| CMDCOR,MENU             | Shows MiSTer Menu |
| CMDCOR,CORENAME         | Shows picture/video from SD (filename) |
| CMDSETTIME,TSTAMP       | Set time and date (timestamp) |
| CMDVIDEOPLAY,PARAM      | Play videos or not (yes/no/may) |
| CMDSAVER,PARAM,PARAM    | Screensaver after x mins. (1-59), change after y secs, (1-59) |
| CMDHWINF                | Send hardware info, BuildVersion and MAC address |

If a picture/video can't be found on SD and WiFi isn't available, show a "...not found..." picture.
But is WiFi available load a **picture** (but not a video) from archive.org and save it on SD.
An upload with CMDUPLOAD saves the picture/video on SD.


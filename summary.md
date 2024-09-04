# index
API summary for the Playhead.

# STABLE

no endpoints stable yet

# BETA

## device
Endpoints to manage device

### audio
**/device/audio/list (GET)**
List available audio devices, possibly with info about lowest buffer etc.
DATA: TBA

**/device/audio/doSelect (POST)**
Set audio device to work with. We probably can't set samplefrequency etc. Just select device.
DATA: TBA

**/device/audio/doStart (POST)**
No arguments

**/device/audio/doStop (POST)**
No arguments

**/device/audio/status (GET)**
Returns JSON info of audio service - really - why?

### midi

**/device/midi/list (GET)**
List available midi devices, with direction specified.
DATA: TBA

**/device/midi/doSelectIn (POST)**
Set midi device(s) to work with. We may use many midi devices for in right?
DATA: TBA

**/device/midi/doSelectOut (POST)**
Set midi device(s) to work with. For out, only ONE device may be selected.
DATA: TBA

**/device/midi/doStart (POST)**
No arguments

**/device/midi/doStop (POST)**
No arguments

**/device/midi/status (GET)**
Returns JSON info of midi service

## synth_patches
Outside song storage

## rack_patches
Outside song storage

## songs
Endpoints to manage songs

**/songs/list (GET)**
List songs on device

**/songs/doCopy (POST)**

**/songs/doDelete (POST)**
(why not the delete method?)



## rack settings


## patterns
Part of song and rack, right?





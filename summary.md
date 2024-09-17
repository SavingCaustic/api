# index
API summary for the Playhead.

# STABLE

no endpoints stable yet

# BETA

## device
Endpoints to manage device

### general
**/device (GET)** 
Get all parameters for device

**/device (PUT)**
Updates all parameters for device

### audio
**/device/audio/list (GET)**
List available audio devices, possibly with info about lowest buffer etc.
DATA: TBA

**/device/audio/doStart (POST)**
No arguments

**/device/audio/doStop (POST)**
No arguments

**/device/audio/status (GET)**
Returns JSON info of audio service

### midi

**/device/midi/list (GET)**
List available midi devices, with direction specified.
DATA: TBA

**/device/midi/doStart (POST)**
No arguments

**/device/midi/doStop (POST)**
No arguments

**/device/midi/status (GET)**
Returns JSON info of midi service

## songs
Endpoints to manage songs

**/songs/list (GET)**
List songs on device

**/songs/doCopy (POST)**

**/songs/doDelete (POST)**
(why not the delete method?)





## synth_patches
Outside song storage

## rack_patches
Outside song storage


## rack settings


## patterns
Part of song and rack, right?





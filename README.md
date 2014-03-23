##Install Steps(version 4.1.1_r6)##

### Preparation ###
Ubuntu 13.10(x64) is recommended

### Step 1: Get and build the Android source code ###

% mkdir -p ~/DiSLDroid
% cd ~/DiSLDroid
% repo init -u https://android.googlesource.com/platform/manifest -b android-4.1.1_r6
% repo sync

__Note__: You have to verify that the original android emulator works before continuing next steps. Build steps referring to _http://source.android.com/source/downloading.html_


### Step 2: Install the Patch ###



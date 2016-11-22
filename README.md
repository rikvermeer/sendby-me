# sendby-me: A progressive HTML5 WebRTC file transfer app

The goal is to make transfer between devices peer-to-peer and easy.

## Transfer files between devices

### Step 1: (device 1)
Select files

### Step 2: (device 2)
Make picture of generated qr-code

## How it works
A qr-code is generated from the selected files' hashcode combined with the random generated user-id of the senders.
The remaining hashcode is used as an identifier to announce the channel over Google's Firebase.
Stun is then used to negociate RTC.

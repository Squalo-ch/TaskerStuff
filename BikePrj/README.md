# Bike Riding Profiles

Profiles for task automation when riding the motorcycle. Phone is on a holder on the handlebars, connected to the helmet BT intercom.

## Riding On

Triggers the *RidingVarOn* task (the task simply toggles the variable %RIDING on). This task (*RidingVarOn*) can also be activated with an toggle button icon on the phone or reading a NFC tag sticker on the bike (with the task *MotoRide*).

### MotoRide task

Turns BT on and WiFi off, and sets variable %RIDING to *on* (or opposite). Gives feedback with a screen message confirmation and an audible beep (that normaly can be hear with helmet on and the engine running).

## Riding Settings

The phone settings and list of profiles to turn *on* or *off* according to the %RIDING variable status:
* Phone volume setting.
* Phone screen brightness (and timeout).
* Profile for incoming calls (say caller name or number).
* Profile to read incomming SMS.
* Profile for calls unanswered from selected contacts.
* Profile to read messages from messaging apps.

## Receive a text message while riding (Receive_Text_Bike)

If the phone gets an incomming text whilst the helmet bluetooth is connected it will pause the music player and read the SMS message. The music player is restarted after 1 minute. Additionally it will calculate the current speed and reply to the sender that I'm currently riding (at the calculated speed) and will reply when safe.

### Convert_LOCSPD_KMH

This task converts the raw speed data into km/h

## Incomming call while riding (Receiving_Call_Riding)

For incomming calls from any of my contacts, when my helmet BT is connected, this profile will pause the media player and say the caller's name. The call can be taken or dodged.

## Missed or dodged call while riding (Dodge_Call_Bike)

On the event of a missed call from any of my contacts, it will say the caller's name and reply back with an SMS stating that I'm riding (with my current speed) and will reply when safe.

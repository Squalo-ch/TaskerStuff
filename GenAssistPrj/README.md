# General Assistance Profiles

## Findme

(Cannot find the phone? No worries... make it shout!).

Upon receiving an SMS with the text 'Findme' the phone will save the current media volume levels and then bring the volume to the max. Then it will beep and speak out 'Hey!!' (or whatever you whant it to say) 4 times and then bring back the media volume to original level.

## Locate SMSGPS

(When no-one answers the phone and people starts to get worried!).

When a contact registered on the I.C.E. group (emergency contacts) sends an SMS with 'Gps', get the GPS location and send it.

## Low Battery

(Because sometimes the phone alert alone is not enough!).

If the battery level gets below 8%, a text message to a given number is sent. Note: if the alert is to be sent to someone away, make sure the % level is set with enough margin to allow for an incoming call.

## Missed Call

(When the phone is on the other room or in the hand-bag, and someone really is trying to reach you!).

On the event of an unanswered call, the incoming number is saved. If the same number is missed again in less than 30 minutes, a timer is started and a missed call count is increased by 1. Once the counter gets > 2, the volume of the ringtone is set to max and the phone vibration is enabled. The 4th incoming call will then have full volume and vibration. After 30 minutes of the last call missed call, the count is reset to 0.

## WIFI Start/Stop

(Automatically enable WiFi when at home and disable when on the move!).

This profile has been copied and adapted from the **Wifi Automator** from the **Tasker Wiki** (http://tasker.wikidot.com/wifi-automator).

## Autostart

Just to make sure the main and emergency profiles are turned ON in the event of a re-start.


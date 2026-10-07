# CarPlay audio route not restored after phone call

## Title

CarPlay audio route not restored after phone call

## Date discovered

2026-09-28

## Product / system

Apple CarPlay / iOS audio routing

## Device / hardware

- iPhone 14 Pro Max
- Toyota Yaris, 4th generation

## Software version

iOS 27.0, as recorded when the problem was discovered.

## Environment

An iPhone connected to CarPlay in a Toyota Yaris, with media playback active before a phone call. During the call, the call audio output is changed from CarPlay to the iPhone speaker.

CarPlay connection type (wired or wireless), media application, and infotainment firmware version: not recorded.

## Problem

When a phone call is routed from CarPlay to the iPhone speaker during the call, ending the call does not restore media playback to CarPlay. Music continues playing through the iPhone speaker.

## Expected behavior

After the phone call ends, media playback should return automatically to the active CarPlay audio route.

## Actual behavior

After the call ends, media playback remains routed to the iPhone speaker instead of CarPlay.

## Steps to reproduce

1. Connect the iPhone to CarPlay.
2. Start media playback through CarPlay.
3. Start a phone call.
4. During the call, change audio output from CarPlay to the iPhone speaker.
5. End the call.
6. Observe that media playback remains routed to the iPhone speaker instead of CarPlay.

## Reproducibility

Unknown — the number of attempts and success rate were not recorded.

## Workaround

1. Start another phone call.
2. Switch the call audio output back to CarPlay.
3. End the call.

Media playback returns to CarPlay after this sequence.

## Possible cause / hypothesis

Not established. The behavior is associated with changing the call audio output to the iPhone speaker; the underlying cause has not been confirmed.

## Reported upstream

Not recorded.

## Upstream report

Not recorded.

## Status

Workaround available

## Notes

This entry documents the observed behavior and workaround. It does not establish the root cause, behavior on other devices or versions, or an upstream fix. No upstream report was provided with this entry.

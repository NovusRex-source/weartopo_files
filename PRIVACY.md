# WearTopo – Privacy Policy

_Last updated: 2026-10-19_

WearTopo is a map and navigation app for Wear OS watches. This policy explains what data the app
handles. **Replace the contact line at the bottom with your own before publishing**, and host this text at
a public URL for the Play Console "Privacy policy" field.

## What stays on your watch
- **Your precise location.** Used to show your position on the map, to record a track, to follow a route
  and for the emergency screen. Location is only read while the app is open or while you have started a
  recording or route navigation (a visible ongoing notification is shown). It is **never sent to the
  developer** and never uploaded anywhere by the app.
- **Saved places, imported routes, recorded tracks, settings and downloaded offline maps.** They are stored
  in the app's private storage on the watch. They are excluded from cloud backup and device transfer.
  Uninstalling the app deletes them. You can delete routes, places and offline maps inside the app.

## What is sent to third parties
The app contacts these servers to work. They receive the data a normal web request contains (your IP
address and the request itself). The developer receives none of it.
| When | Data sent | To |
|---|---|---|
| Showing the map | Map tile coordinates (which area you look at) | `wmts.geo.admin.ch` (swisstopo) |
| Searching | Your search text | `api3.geo.admin.ch` (swisstopo) |
| Long-pressing the map | The pressed point and visible map area | `api3.geo.admin.ch` (swisstopo) |
| Importing a route by link or name | The link you entered | The server in the link (default `s.geo.admin.ch`, or the server you set) |
| Downloading an offline area | Map tile coordinates of that area | `wmts.geo.admin.ch` (swisstopo) |

swisstopo's own privacy statement applies to these requests: <https://www.geo.admin.ch/en/privacy-policy>.

## What the app does not do
No accounts, no advertising, no analytics, no crash-reporting service, no tracking, no sale or sharing of
personal data. Location is not used in the background when no recording or navigation is running.

## Permissions
- **Location (precise and approximate):** position on the map, track recording, route following.
- **Foreground service (location):** keeps recording/navigation running while the screen is off.
- **Notifications:** shows the ongoing recording/navigation status.
- **Vibration:** off-route and arrival alerts (can be switched off in Settings).
- **Internet:** map tiles, search, feature lookup and route download.

## Emergency screen
The emergency screen shows your coordinates and opens the phone dialer for 112, 144 or 1414. It does not
place calls or send messages by itself. WearTopo is a navigation aid, not a safety device: do not rely on
it as your only means of navigation or emergency communication.

## Children
The app is not directed at children and collects no personal data from anyone.

## Changes
If this policy changes, the new version will be published at the same address with a new date.

## Contact
Noel Wangler - NoW Photography, store@noelwangler.ch

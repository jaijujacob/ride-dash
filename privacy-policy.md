---
title: Ride-Dash privacy policy
---

# Ride-Dash — Privacy Policy

_Last updated: 28 November 2026 (version 1.18.1)_

Ride-Dash is a car dashboard and home-screen launcher. It has no user accounts, no analytics and no advertising. Apart
from **Group ride** (below), which you use only if you create or join a group, it has no server of its own.

## Location

Ride-Dash uses your device's location **while the app is in use** to show speed, heading, the map, trip distance and
the trip log. If you turn on "Track trip in background", a foreground service with a visible notification keeps
counting the trip while another app is on top. Ride-Dash does not request background location permission.

- **Trip log:** finished trips (times, distances, speeds, start/end coordinates and a GPS track) are stored **only on
  your device**, in the app's private storage. They leave the device only if you export them yourself (Settings ›
  Trip & speed › Export trips to Excel) and choose where to save or share the file. "Delete all trip data" removes
  them permanently; uninstalling the app also removes them.
- **Weather (optional, on by default):** to show the outside temperature, an approximate position (rounded to about
  1 km) is sent to [Open-Meteo](https://open-meteo.com/) at most every 20 minutes. You can turn this off in
  Settings › Display.
- **Speed breakers (optional, on by default):** to warn before speed breakers, the app downloads the speed breakers
  mapped in [OpenStreetMap](https://www.openstreetmap.org/) for about 5 km around you from the
  [Overpass API](https://overpass-api.de/), sending an approximate position (rounded to about 1 km). This happens only
  when you reach an area not downloaded in the last 30 days; the results are kept on your device. Speed breakers you
  mark yourself stay **only on your device**. You can turn this off in Settings › Trip & speed.
- **Speed limits (optional, on by default):** the speed limits mapped in OpenStreetMap for about 5 km around you are
  downloaded the same way from the Overpass API (approximate position, rounded to about 1 km; only for areas not
  downloaded in the last 30 days; kept on your device). Turn off Settings › Trip & speed › Road speed limits to stop it.
- **Places on older head units:** on units that show the picture-tile map, the places for the map (fuel stations,
  ATMs, hospitals…) for about 5 km around you are taken from MapTiler's map tiles for that area (the same service that
  supplies the map), or — if that fails — from the Overpass API (approximate position, rounded to about 1 km; only for
  areas not downloaded in the last 30 days; kept on your device). Turn off Settings › Map › Show places to stop it.
- **Street names:** the name of the road you are on is read from MapTiler's map tiles for the area around you, on
  every device and map style (the same tiles as the places on older head units; one small tile about every 2 km of new
  road; kept on your device for 30 days). Nothing about the name or your route is sent anywhere.
- **Voice alerts:** spoken by your device's own text-to-speech engine and voice (chosen in Settings, or the best English
  voice installed); Ride-Dash sends nothing for them.
- **Road reports:** speed breakers, cameras, congestion, potholes and other hazards you report with the **Report**
  button or by voice are stored **only on your device** (and in backups you make); they are not shared with other
  users — except, during a group ride, with that ride's members (see Group ride below). Speed and red-light cameras from OpenStreetMap come with the speed-breaker download above (same request,
  approximate position, no extra data).
- **Map tiles:** the map downloads map images for the area on screen from the
  [MapTiler](https://www.maptiler.com/) (Classic map style; tiles made from OpenStreetMap data) or
  [OpenFreeMap](https://openfreemap.org/) (Modern map style). As with any map, the requested area reveals the approximate region being
  viewed. No identifiers are added by Ride-Dash.

- **Parking spot:** when a trip ends, its last good position is saved as your parking spot ("Where's my car").
  The last 10 spots stay **only on your device**; sharing one is up to you.
- **Navigation:** when you long-press a place on the map, pick a search result, and confirm **Navigate**, your current
  position and the destination are sent to [GraphHopper](https://www.graphhopper.com/) to calculate the route shown
  on Ride-Dash's map; while you drive, a new route is requested the same way when you leave the old one. With
  **Google Maps** instead, the destination's coordinates are handed to Google Maps (or another navigation app you have
  installed). Nothing is sent unless you confirm.
- **Place search:** the text you type in the map's search box and your current position (to list nearby places first)
  are sent to GraphHopper when you press Search. Ride-Dash keeps neither the searches nor the routes.
- **Your own GraphHopper key (optional):** a key you enter in Settings › Map › Navigation is stored encrypted on your
  device (not in backups) and sent only to GraphHopper with your routes and searches. **Test key** sends just the key
  to GraphHopper to check it and show the credits left today.
- **Sights on the map** (viewpoints, monuments and similar) come from the same map data; no extra data is sent.

## Microphone (voice reports)

Only when you tap the **microphone** button on the dashboard, Ride-Dash listens once for a road report ("camera",
"traffic", "pothole"…) through your device's built-in speech recognition, preferring its offline mode. Ride-Dash keeps
only the report type it recognised; it does not record or store audio, and never listens in the background or for a
wake word. Recognition is done by your device's speech service (for example Google's) under its own privacy terms. The
microphone permission is asked the first time you tap the button and can be revoked in Android's settings at any time.

## Group ride (optional)

Group ride lets friends who ride or drive together see each other on the map. It is used only if you create or join a
group (by link, QR code or a 6-character code).

- **What is shared:** the name and phone number you enter, your vehicle's name, a colour, and — once the leader has
  started the ride — your live position (latitude, longitude, speed, heading, time). The group's other members see
  them on their map so they can find and call you. A planned ride also shares its plan (start, stops, destination,
  planned times and route) and when members reach a stop. While the ride runs, road reports you make (type, position,
  time and, for cameras, the direction) and a **Fuel stop** or **Breakdown** alert you send (with your position and your
  vehicle's name) are shown to the group's members. Members keep the others' reports and alerts in memory only.
- **Where:** in Google Firebase (Realtime Database, Anonymous Authentication, Cloud Messaging and Cloud Functions) on
  servers operated by Google for Ride-Dash, encrypted in transit. Firebase gives each installation an anonymous ID; no
  account, email or password is involved. A Firebase messaging token lets the group reach your device (for example
  "the ride has started") when the app isn't open.
- **No history online:** only your latest position is stored, overwritten as you move. Nothing is shared before the
  leader starts the ride; sharing stops when you tap **Stop sharing** or leave, and the notification shows while it runs.
- **Deletion:** when the leader ends the group, or 24 hours after the last activity (for a planned ride that hasn't
  started, 24 hours after its planned start), the group and all its data — positions, names, phone numbers, the plan —
  are deleted from the server automatically, including the shared reports and alerts. When you leave, your own entries
  are deleted at once.
- **On your device:** a summary of finished group rides (members' names and vehicles, stop times; other members' phone
  numbers only if you choose) and saved group ride plans stay **only on your device** for the export and backups you
  make. Scanning a QR code uses the camera on the device only; nothing is uploaded.
- **Installing from a group link:** when a friend's link sends you to Google Play, Google Play passes the group's code to
  the app (install referrer) so it can open "Join {group}?" on the first start.
- Ride-Dash has no access to the data beyond running the service, does not sell it, and does not use it for anything
  else.

## Notifications and media

With your permission (notification access), Ride-Dash reads the currently playing track from media apps and the
next turn from Google Maps / Waze navigation notifications, to show them on the dashboard. This information is used
on the device only and is not stored or transmitted.

## Other data

- Settings and images you upload (logo, car image, background) are stored only on the device.
- Ride-Dash reads the list of installed apps to show the app drawer and dock; this list stays on the device.
- No personal information (name, email, contacts, photos) is collected, except the name and phone number you enter for
  Group ride, which are shared only with your group as described above.
- **Backup files:** *Back up trip data* writes a file with your trips (times, distances, the places they started and
  ended, and route points if you include them), parking spots, the speed breakers you marked and, if you choose, your
  settings, your road reports, saved routes and group ride plans, finished group rides (other members' phone numbers only
  if you tick that option) and your group ride name and phone. Ride-Dash creates it only when you ask and saves it only where you choose (or hands it to the app you pick to
  share it); it doesn't send it anywhere itself. Your own GraphHopper key and your pictures are not included.
- **App updates:** on copies installed from Google Play, Ride-Dash asks Google Play whether a newer version exists (when
  you tap *Check* in Settings › About, and by itself about once a week) and, if you agree, Google Play downloads and
  installs it. That exchange is between your device and Google Play under
  [Google's privacy policy](https://policies.google.com/privacy); Ride-Dash adds nothing to it. Copies installed from
  the APK file don't check.

## Children

Ride-Dash is not directed at children.

## Changes and contact

Changes to this policy will be published with app updates and on this page. Questions: [ridedash.app@gmail.com](mailto:ridedash.app@gmail.com)

[Back to the home page](index.html)

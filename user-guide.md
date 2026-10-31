---
title: Ride-Dash user manual
---

# Ride-Dash user manual

_Version 1.5.0 · October 2026_

Ride-Dash turns the phone in your holder — or your car's Android head unit — into a calm, complete car dashboard:
live speed, gear, heading and altitude, the road you are on and its speed limit, trip statistics, terrain, speed
breaker and break alerts spoken aloud, music, the map with the places you choose, and "Where's my car". Everything
works on the device; no account needed.

![Ride-Dash in the Duo layout](images/manual/duo_white_driving_1600x720.png)

**Contents:** [What's new](#whats-new-in-150) · [1 Installing](#1-installing) · [2 First start](#2-first-start) ·
[3 The dashboard](#3-the-dashboard) · [4 Layouts and colours](#4-layouts-and-colours) · [5 Speed and speed limits](#5-speed-and-speed-limits) ·
[6 Driving mode, terrain and road info](#6-driving-mode-terrain-and-road-info) · [7 Map](#7-map) ·
[8 Places on the map](#8-places-on-the-map) · [9 Music](#9-music) · [10 Trips](#10-trips) ·
[11 Breaks](#11-break-reminder) · [12 Speed breakers](#12-speed-breakers) · [13 Voice alerts](#13-voice-alerts) ·
[14 Where's my car](#14-wheres-my-car) · [15 Settings](#15-settings-reference) ·
[16 Export and storage](#16-export-storage-and-deleting-data) · [17 Troubleshooting](#17-troubleshooting)

## What's new in 1.5.0

- **Road speed limits:** a speed-limit sign for the road you are on (from OpenStreetMap, where mapped), and
  "Slow down" at that limit plus a tolerance you choose (section 5).
- **Street name and road info:** the road you are on, the terrain with its gradient ("UPHILL 6 %") and the next speed
  breaker, shown where turn-by-turn normally appears (section 6).
- **Places of your choice on the map:** fuel, EV charging, ATMs, hospitals, toll booths, hotels, viewpoints, places of
  worship and more — tick the ones you want, each with its own icon (section 8).
- **Navigate to a long-pressed place** by name, also on older head units (section 7).
- **Turn-by-turn without a box:** the next turn sits right on the dashboard in every layout.
- **Start-up sweep:** the dials light up and sweep their needles once when Ride-Dash starts (tap to skip).
- **Every layout tidied up:** bigger maps that reach the frame, the driving style as an icon and coloured word, the
  rest bar with the coffee cup after it, rpm in the dial, cleaner info bars.
- White is now the default colour scheme for new installs.

## What's new in 1.3.0

- **Speed breaker alerts:** "Humps ahead · 150 m" before speed breakers on the road ahead, from OpenStreetMap and your
  own marks. One tap on the hump button marks a new one.
- **Voice alerts:** break reminder, "Slow down" and "Speed breaker ahead" spoken through the car speakers; music gets
  quieter meanwhile.
- **Terrain:** FLAT, UPHILL, DOWNHILL, WINDING or GHAT while you drive, and the share of each in the trip log.
- **Where's my car:** your parking spot is saved when a trip ends; walking directions back to it.
- **Waiting for GPS:** the dashboard shows `--` and the satellites found instead of looking frozen; the map starts at
  your last position; GPS starts sooner on head units.
- **Gauges wake up at once** when you drive off after a long stop.
- **Demo mode** for trying everything at your desk (Settings › About, tap the version 7 times).

## 1. Installing

**Phone (Google Play):** search for **Ride-Dash** in Google Play and tap **Install**. Android 8 or newer.

**Car head unit (APK file):** most Android head units can't reach Google Play, so Ride-Dash is installed from a file.

1. Copy `Ride-Dash-<version>-release.apk` to a USB stick (FAT32 or exFAT) and plug it into the unit.
2. Allow installing apps from the file manager: *Settings › Security › Unknown sources* on older units, or
   *Settings › Apps › Special access › Install unknown apps › (file manager) › Allow*. Some units hide this behind a
   factory code — see the unit's manual.
3. Open the file manager, tap the APK, choose **Install**.
4. "App not installed": free about 100 MB of storage and try again; check the unit runs Android 8 or newer
   (*Settings › About*).

Updates install the same way over the old version; your settings and trips are kept.

## 2. First start

1. **Location** — tap **Continue** and allow location "While using the app". Speed, trips, the compass and the map all
   come from GPS.
2. **Notifications** — allow them: the trip keeps counting while other apps are in front.
3. **Music and navigation info (optional)** — *Settings › Launcher & apps › Music controls & track info › Allow* lets
   Ride-Dash show the song and the next turn from Google Maps or Waze.
4. **Head units:** *Settings › Launcher & apps › Set as default home app* (Ride-Dash opens with the car), and
   *Start on boot*.

**Waiting for the first GPS fix.** Until GPS knows where you are, the speed shows `--` and the trip display reads
`SEARCHING GPS · 3/11 SATS` (satellites used / in view). A phone usually needs seconds; a head unit can need a few
minutes the first time, especially indoors.

![Searching for GPS](images/manual/duo_white_searching-gps_1600x720.png)

Head-unit tips: the GPS antenna (a small square puck on a cable) must see the sky — put it under the windscreen or the
dashboard top, not inside the glovebox or under metal. Wait outdoors with the engine running the first time. *Settings
› About* shows how long the first fix took.

## 3. The dashboard

![The dashboard](images/manual/duo_white_driving_1600x720.png)

| Where | What |
| --- | --- |
| Top left | Your logo and vehicle name; alerts appear here (break, speed breakers) |
| Top centre | Time, weather, sunrise / sunset, battery, weekday and date |
| Top right | GPS status, settings, power (end trip and exit) |
| Driving style | ECO · CITY · IDLE · SPORT — an icon and a coloured word |
| Speedometer | Speed with colour zones; gear and rpm (estimated); the other unit nearby |
| Compass and road | Heading, direction, altitude above sea level; the road animation moves with your speed |
| Road info | Street name, terrain with gradient, next speed breaker — or the next turn while navigating |
| Trip display | Drive mode, terrain, distance, moving time, top and average speed |
| Map | Where you are, heading up; the places you chose, speed breakers, your parked car; speed-limit sign |
| Bottom left | **Hump button** (mark a speed breaker), music controls and track |
| Bottom right | Speed bar and break (rest) bar — driving time, bar, coffee cup |

The arrangement differs per layout, but every layout has the same pieces.

## 4. Layouts and colours

*Settings › Appearance.* Pick a **layout** (the arrangement) and a **colour scheme** (the colours) separately.

| Layout | The look |
| --- | --- |
| Open | Frameless: a huge digital speed and big trip readings |
| Lap | Racing visor, speed inside the rpm arc |
| Duo | GT cluster with a wide map |
| Cockpit | One ring gauge in the middle |
| Classic | Analogue speedometer, compass and road |
| Sport | Big centred speedometer |
| Modern | Fully digital cluster |
| Twin | Speedometer and rev counter with a map window |

![Open](images/manual/open_white_driving_1600x720.png)
![Lap](images/manual/lap_white_driving_1600x720.png)
![Cockpit](images/manual/cockpit_white_driving_1600x720.png)
![Classic](images/manual/classic_white_driving_1600x720.png)

Colour schemes: White (default), Amber, Blue, Red, Green, Titanium and Bronze — or choose your own display colour.
You can also upload a background image, your logo and a picture of your car (*Settings › Vehicle*).

![Duo in Blue](images/manual/duo_blue_driving_1600x720.png)

## 5. Speed and speed limits

- The big number is your speed in your colour scheme; the needle, arc and speed bar change colour with speed:
  **green** below 50 km/h, **amber** from 50, **red** from 80, darkest red at 120. Change the limits in
  *Settings › Trip & speed › Speed colours*.
- The other unit (mph or km/h) is shown smaller. Switch the main unit in *Settings › Trip & speed › Unit*.

**Road speed limit.** Where OpenStreetMap knows the speed limit of the road you are driving, a round sign shows it on
the map (in Lap beside the driving style). Ride-Dash picks the road you are driving along, so a side road you cross
doesn't take over. Above the limit plus your **tolerance** (+0, +5 or +10 km/h; default +5) the number on the sign
turns red, the drive mode shows **SLOW DOWN** and, with voice alerts, you hear "Slow down. Speed limit 60."

![Speed limit](images/manual/duo_white_speed-limit_1600x720.png)

Where no limit is mapped — still many smaller roads in India — the sign is hidden and the old rule applies: SLOW DOWN
at 80 % of the speedometer's scale, the voice at the red speed colour.

The limits are downloaded for about 5 km around you from OpenStreetMap (your position rounded to about 1 km) and kept
on the device for 30 days. *Settings › Trip & speed › Speed limits:* on/off and the tolerance.

![Speed breaker and speed limit settings](images/manual/settings_trip-alerts_1600x720.png)

![Overspeed](images/manual/duo_white_overspeed_1600x720.png)

## 6. Driving mode, terrain and road info

**Driving style** (icon and coloured word): **ECO** smooth and steady · **CITY** slow, stop-and-go traffic · **IDLE** standing more
than 30 s in a trip · **SPORT** brisk acceleration, braking or cornering. It comes from GPS alone and changes after a
few seconds, so one brake at a signal doesn't flip it.

**Drive mode** (trip display header): READY, STUCK IN TRAFFIC, CITY DRIVING, CRUISING, HIGHWAY CRUISE, ACCELERATING,
BRAKING, OVERSPEED, PARKED.

**Terrain** (next to it while you drive):

| Word | Meaning |
| --- | --- |
| FLAT | Little height change, mostly straight |
| UPHILL / DOWNHILL | A steady climb or descent, steeper than about 4 % |
| WINDING | Many bends |
| GHAT | Winding and climbing or descending — a hill road |

On climbs and descents the gradient is added: **UPHILL 6 %**, **DOWNHILL 5 %**, **GHAT 8 %**. A new word appears only
after it has held for 15 seconds. Phones with a barometer (most) measure height changes
precisely; head units use GPS height. The trip log shows how much of each trip was in each terrain.

![Ghat road](images/manual/duo_white_ghat-break-alert_1600x720.png)

**Road info.** When no route is running, the place where turn-by-turn normally appears shows:

- the **street name** of the road you are on, with its route number ("Ettumanoor - Ernakulam Road · SH15");
- the **terrain** with its gradient;
- the **next speed breaker** on your road ("Hump in 350 m" up to 2 km ahead, or "No humps ahead"), when speed breaker
  alerts are on.

The street name comes from the map itself, so it needs no extra data. It keeps the current road at junctions instead
of flickering. On older head units that show the picture-tile map, street names aren't available and only the
terrain and speed breaker lines appear. In some layouts the street name only appears once the map is zoomed in far
enough to show street names.

Where it shows: Duo and Lap under the map or compass, Classic and Twin beside the compass, Modern, Sport and Cockpit over
the top of the map, Open over the road animation. While Google Maps or Waze is navigating, the **next turn** (arrow,
distance, instruction) takes its place.

## 7. Map

- **Heading-up:** the map turns with the car (north-up in *Settings › Map*).
- **Map style:** *Classic* (dark street map, default) or *Modern* (a crisper vector map, on devices whose graphics allow it).
- **Places:** the places you choose (section 8). The places button on the map shows or hides them all.
- **Full screen:** the expand button fills the screen with the map; Back returns.
- **Next turn** from Google Maps or Waze appears on the dashboard while they navigate (needs the access in step 2).
- Speed breakers show as red-bordered road signs; your parked car as a blue **P**.

**Navigate to a long-pressed place.** Press and hold any spot on the map for about a second:

1. Ride-Dash names the place under your finger — a shop, a landmark, or the road — and asks **"Navigate to MASS
   Road?"** (or "Navigate here?" where there is no name), with how far away it is.
2. **Navigate** opens Google Maps with directions by car from where you are; without Google Maps, any installed
   navigation app is offered. **Cancel** or wait 15 seconds to close the question.

![Navigate to a long-pressed place](images/manual/duo_white_navigate_1600x720.png)

On older head units with the picture-tile map, press and hold a place icon to navigate to it by name; elsewhere the
pressed spot is used. Press and hold one of **your own speed breakers** to delete it instead (section 12).

## 8. Places on the map

*Settings › Map › Map points of interest* (under **Show places**): tick the places you want to see. Each group has
**Select all / Select none**; changes show on the map at once.

| Group | Places (ticked when you install) |
| --- | --- |
| Essentials | **Fuel stations**, **EV charging**, **ATMs**, **Hospitals**, Pharmacies, **Police stations**, Toilets |
| Vehicle | **Car service / repair**, **Tyre / puncture repair**, Car wash, **Parking**, **Toll booths** |
| Food & rest | **Restaurants**, Cafés / tea shops, Fast food, **Hotels / motels / lodges**, **Rest areas** |
| Travel | Railway stations, Bus stations, Airports |
| Sightseeing | **Viewpoints / photo points**, Tourist attractions, Beaches, Waterfalls, Museums, Parks, Places of worship, Cinemas |

![Map points of interest](images/manual/settings_map-places_1600x720.png)

- Every type has its own icon in your display colour; places of worship show a church, mosque, temple or other icon by
  religion.
- To keep the map calm, only a few icons show when zoomed out — essentials first — and food appears once you zoom in to
  street level. Names appear close up.
- **Show places** off hides them all.
- On phones and newer head units the places come with the map itself. On older head units (picture-tile map) they are
  downloaded from OpenStreetMap for about 5 km around you, one group at a time, and kept for 30 days — the first time
  in a new area they can take a minute to appear.

## 9. Music

The music panel shows the playing track, a seek bar and large **previous / play-pause / next** buttons on the left
(within reach even with a phone holder in the middle of the screen). It follows whatever app is playing: Spotify,
YouTube Music, the radio app, Bluetooth audio.

- Needs *Music controls & track info* access (step 2). Without it the buttons still work.
- **Head units:** Bluetooth music from your phone shows its title when the unit passes it on (AVRCP); some units keep
  it to their own music app — the buttons still control playback.
- The arrow at the left switches between the music panel and your favourite apps (*Settings › Launcher & apps ›
  Choose dock apps*).

## 10. Trips

- A trip **starts by itself** after about 10 seconds above 7 km/h and 50 m moved — walking or GPS drift never starts
  one.
- It **ends** after you have stood still for 5 minutes (*Settings › Trip & speed › End trip after stopped for*), or
  with the power button (End trip & exit). Short stops at signals don't split a trip.
- **Power cut or ignition off:** the trip is saved every few seconds; next time it is closed at its last saved point
  and marked "auto (power off)" in the export.
- The trip display shows **TRIP** (distance), **TIME** (moving time), **MAX** and **AVG** (moving average).
- Trips shorter than 200 m or 1 minute are not kept.
- *Settings › Trip & speed › Trip log* lists your trips; export them to Excel (section 16).

## 11. Break reminder

The rest bar (driving time, the bar, then the coffee cup) fills from left to right with your continuous driving time (green, amber in the last 30 minutes, red with BREAK when
due). After **2.5 hours** (*Remind after*), **Time for a break** blinks at the top left — never over the speed or the
map — and is spoken. Tap it to snooze for 15 minutes. Short stops pause the timer; standing still for **15 minutes**
(*Break length to reset*) starts it afresh.

![Break alert](images/manual/duo_white_ghat-break-alert_1600x720.png)

## 12. Speed breakers

**Humps ahead · 150 m** appears in red at the top left before a speed breaker on the road ahead, about 9 seconds
early at your speed (80–300 m), and you hear "Speed breaker ahead". Only humps on the road you are driving count —
not those on side roads or behind you. A group of humps close together gives one alert; nothing below 15 km/h. The
banner clears once you're past.

![Humps ahead](images/manual/duo_white_humps-alert_1600x720.png)

**Where the humps come from:** OpenStreetMap, the free world map anyone can improve. Ride-Dash downloads the speed
breakers within about 5 km of you (sending only a position rounded to about 1 km) and keeps them on the phone, so
roads you have driven before work offline.

**Map your own speed breakers.** Many Indian humps are not in OpenStreetMap yet. As you drive over one, tap the **hump
button** (the red hump sign at the bottom left of the dashboard). It is saved at your position — "Speed breaker marked"
confirms it — shows on the map as a sign, and alerts you like the others from then on. Your marks stay only on this
device.

**Remove one of yours:** press and hold it on the map → **Delete this speed breaker?** → **Delete**. Speed breakers from
OpenStreetMap can't be deleted (they are fixed in OpenStreetMap itself).

**Next speed breaker:** the road info (section 6) shows how far the next one on your road is, up to 2 km ahead.

*Settings › Trip & speed › Speed breakers:* on/off and **Alert distance** Near / Normal / Far.

## 13. Voice alerts

Spoken through the car speakers like navigation (music gets quieter, then comes back):

- "You've been driving for two and a half hours. Time for a break." (your configured time)
- "Slow down. Speed limit 60." after 3 seconds above the road's limit plus your tolerance (or the red speed colour where
  no limit is mapped); again only after slowing 5 km/h below it, at most once a minute.
- "Speed breaker ahead."

*Settings › Trip & speed › Voice alerts:* on/off, a switch per alert, and **Test**.

**No voice on a head unit?** Many units have no text-to-speech engine. Settings then says so, and alerts beep instead.
To get voices: install **Speech Services by Google** (Play Store, or its APK on units without Play), open *Android
Settings › Text-to-speech*, choose it as the engine, download the **English (India)** voice, and restart Ride-Dash.

## 14. Where's my car

When a trip ends, the last good GPS position is saved as your parking spot — even in a covered car park where the
signal got weak at the end. Tap the **P** button on the map:

![Where's my car](images/manual/duo_white_wheres-my-car_1600x720.png)

- how long ago you parked and how far away the car is;
- **Navigate:** walking directions in Google Maps;
- **Share:** send the location to someone.

The last 10 spots are in *Settings › Trip & speed › Parking history* and in the Excel export.

## 15. Settings reference

| Page | Setting | Default |
| --- | --- | --- |
| Appearance | Dashboard layout | Classic |
| Appearance | Colour scheme · custom colour | White · none |
| Appearance | Background image | none |
| Vehicle | Vehicle title | Ride-Dash |
| Vehicle | Brand logo · car image | app icon · none |
| Vehicle | Engine & gearbox preset (for gear / rpm) | Diesel SUV · 5-speed manual |
| Vehicle | Tyre size, gear ratios, final drive, idle, redline, automatic | from the preset |
| Trip & speed | End trip after stopped for | 5 min |
| Trip & speed | Break reminder · remind after · break length · alert sound | on · 2.5 h · 15 min · off |
| Trip & speed | Cruising above | 60 km/h (highway 90) |
| Trip & speed | Unit | km/h |
| Trip & speed | Speed bar full at | 160 km/h |
| Trip & speed | Speed colours: amber / red / darkest red | 50 / 80 / 120 km/h |
| Trip & speed | Speed breaker alerts · alert distance | on · Normal |
| Trip & speed | Road speed limits · tolerance | on · +5 km/h |
| Trip & speed | Voice alerts · break · overspeed · speed breakers | all on |
| Trip & speed | Keep route points for | 90 days |
| Map | Map style | Classic |
| Map | Show places · heading-up · next-turn card | on · on · on |
| Map | Map points of interest | essentials, vehicle, restaurants, hotels, rest areas, viewpoints (section 8) |
| Display | Orientation | Landscape |
| Display | 24-hour clock · driving mode indicator · logo at start-up | on · on · on |
| Display | Full screen | on |
| Display | Keep screen on | While driving / charging |
| Display | Night dimming · level | off · 40 % |
| Display | Weather | on |
| Launcher & apps | Default home app · start on boot | — · off |
| Launcher & apps | Show app dock · dock apps | on · a few common apps |
| Location | Track trip in background | on |

## 16. Export, storage and deleting data

- **Export:** *Settings › Trip & speed › Export trips to Excel* — save the file or share it. One row per trip: times,
  distance, speeds, harsh events, driving style and terrain shares, gears, breaks; a Parking sheet; optionally the
  route points.
- **Storage:** trip summaries are kept until you delete them; route points for 90 days (30 days, 1 year or forever),
  at most 50 MB.
- **Backup:** export to Excel from time to time — your trips exist only on this device.
- **Delete:** *Delete all trip data* removes trips, routes and parking spots. Uninstalling removes everything.
- Nothing is uploaded: see the [privacy policy](privacy-policy.html).

## 17. Troubleshooting

| Problem | Try this |
| --- | --- |
| Speed stays `--`, "SEARCHING GPS" | Go outdoors; on head units check the GPS antenna can see the sky; wait a few minutes the first time. *Settings › Location* — is location allowed? |
| Gauges slow to react after parking | Fixed in 1.3.0 — update. |
| No song title | Allow *Music controls & track info* (Settings › Launcher & apps). Bluetooth music on some head units never sends titles; the buttons still work. |
| No voice | *Settings › Trip & speed › Voice alerts › Test*. If it says there's no engine, install one (section 13). Check the media volume. |
| No speed-limit sign | Most smaller roads have no limit in OpenStreetMap yet; the sign shows only where one is mapped. The first download in an area needs internet. Is *Road speed limits* on? |
| No street name | Phones and newer units only (not the picture-tile map of older head units). Zoom the map in a step. |
| A place type missing on the map | Tick it in *Settings › Map › Map points of interest*; zoom in — some show only close up. |
| No speed breaker alerts | Is the setting on? Are you above 15 km/h? The hump may not be in OpenStreetMap — mark it with the hump button. The first download needs internet. |
| Map is blank | The map needs internet the first time in an area (phone hotspot on head units). |
| Trip split in two | Raise *End trip after stopped for*. |
| App won't install on a head unit | Free 100 MB, check Android 8+, copy the APK again; see section 1. |
| The app closed by itself | *Settings › About › Last crash report › Share* and send it to ridedash.app@gmail.com. |

**Feedback and ideas:** *Settings › About › Send feedback / Request a feature / Report a problem*, or write to
ridedash.app@gmail.com.

[Back to the home page](index.html)

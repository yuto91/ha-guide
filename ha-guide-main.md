# Home Assistant User Guide


## TABLE OF CONTENTS

 1. Getting Started
 2. Google Home Commands
 3. Automations
 4. Future Plans


## GETTING STARTED

Use the official Home Assistant app or a web browser to access the front end.
Home Assistant can be accessed at ***. If using the app, use the following details to set up the connection:
  * URL: ***
  * Pass: ***

Alternatively, you can use Google Home to say commands to Home Assistant. Invoke Google Home with “Hey Google” then follow with a command (e.g. “Turn on Kitchen Lights”). You can see a list of available commands in the next section.
When giving commands, remember:
  * Never use articles like “the”
  * Use “cancel” to abort
  * String together commands with “and” (you must provide an action for each entity, i.e., “turn on kitchen AND turn on living room” rather than “turn on kitchen and living room”)


## Google Home Commands

### Media Center

  * Wii U
  * Apple TV
  * TV On/Off (check)
  * Pause or Pause Music (check)
  * Next or Next Song (check)
  * Play [song/artist/album]
  * Louder
  * Softer
  * Media Center Off (check)

### Lights
  * Downstairs On/Off (check)
  * Entryway Light On/Off
  * Kitchen On/Off
  * Left Kitchen Light On/Off
  * Middle Kitchen Light On/Off
  * Right Kitchen Light On/Off
  * Living Room On/Off
  * Main Light On/Off
  * Light by Window On/Off
  * Pendant Light On/Off
  * Bedroom On/Off
  * Lantern On/Off
  * Floor Lamp On/Off
  * Bedroom Pendant Light On/Off
  * Sjopenna Lamp On/Off
  * Spotlights On/Off
  * Set [light] to...
  * [percent]%
  * Max
  * Full (check)
  * Dim (check)
  * [color]
  * Dim [light] (check)
  * Dim [light group] (check)

### Downstairs – Scenes
  * Turn on Default
  * Turn on Hotline Bling
  * Turn on Theater
  * Turn on/off Color Loop

### Downstairs – Scripts
  * Sleep Mode On
  * Downstairs Off (same as above)
  * Do Not Disturb Downstairs On/Off (check)

### Bedroom – Scenes
  * Turn on Default in Bedroom
  * Turn on Hotline Bling in Bedroom
  * Turn on Theater in Bedroom
  * Turn on/off Color Loop in Bedroom (check)

### Bedroom – Scripts
  * Bedtime
  * Do Not Disturb in Bedroom On/Off (check)

### Miscellaneous
  * Set volume to [0-10]
  * Broadcast
  * Weather
  * Temperature
  * Time
  * Panic (pending)
  * Who’s Home? (pending)
  * Set timer for [num] minutes
  * Set alarm for [time]

### Dev
  * Restart
  * Reload automations
  * Reload scripts
  * Reload groups
  * Sync


## AUTOMATIONS

### Time-based Automations

  * Sunset
    Turns on entryway light just before the sun sets

  * Bedtime Weekday/Weekend
    Turns off bedroom lights and turns on Do Not Disturb for predefined duration of sleep

  * Bedtime Phone Charge Alert
    Warns user before bed if battery is low and phone isn’t plugged in

  * Street Sweeping Alert
    Sends a notification to user’s phone the afternoon before street sweeping begins

### Weather-based Automations

  * Severe Weather Alert
    When a special weather statement is issued, the lights flash red and the statement is     announced on Google Home and shown on the Home Assistant front end

### Device Tracker-based Automations

  * Roommate Is Home
    Lights flash and announcement is made on Google Home when a roommate arrives home (bedroom     only)

  * Guest Is Here
    Lights flash and announcement is made on Google Home when a guest arrives

  * User Home/Not Home
    Bedroom lights turn on/off when a user arrives home

### Other automations

  * Update Available
    Sends a notification to user’s phone when an update for Home Assistant is available

  * Work Commute Alert
    Announces on Google Home and sends a notification to user when the morning commute is expected to take 3 minutes longer than usual

  * Nightly Maintenance Restart
    Restarts home assistant as part of preventative maintenance


## FUTURE PLANS

### Features in progress
    (blank)

### Suggestions for improvement
    (blank)

### Feature requests
    (blank)

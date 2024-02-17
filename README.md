# Functionality

## Host a session

The App plays music streamed over your `Service of choice`.
It manually streams and plays them after each other (without use of In-App-Features like Playlists and Timelines).
It is always looking out for BLE-Advertisement-strings that funktion as profiles as well as seeds for the algorithm.

As soon as a Device is out of range, its seed isnt valued anymore

A host can switch to manual mode (wich can also be requested by a subuser, by connecting to a Virtual Bluetooth Interface,
Created by the Hosts Device (through the App)). there can only be one manual controller at a time. the host can cancel it anytime.

## Participate

On install the user gets asked to authorize with his via his most used Music Streaming Service:

- Spotify
- YT-Music
- AppleMusic

the service will be set as his `Service of Choice` and a seed will be created from his most played genres. (and/or colours and themes)
The seed will automaticaly renew at every Application Startup.


A Manuel Session can be requested by a subuser. He can search and play music over the host's Streaming service. The session
needs to be manually permitted by the host.


A subuser can send Song-Suggestions via BLE.
A subuser can send a Up or Down-Vote for the current Song or Genre via BLE.







All predictions and Algorithms run on the bases, categories and namespaces of the Hosts platform of Choice.
for example: The Artists and Songs are picked among the most played ones by the Host Accound






## *TODO*

- Realtime Player
- Algorithm

- Login (OAuth -> Spotify, AppleMusic, Youtube)
- Seed Generator
- BLE Advertisement
- BLE Checker

- Virtual Bluetooth Device (VBD)
- subuser Socket for VBD


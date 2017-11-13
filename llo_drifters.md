# Low cost data logging drifters

## Terry Brown, Tom Hollenhorst, Jim Berrill, Kaelan Weiss

## EPA, BTS, LLO



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/g2.png" data-background-size="auto" -->



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/g0.png" data-background-size="auto" -->



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/g1.png" data-background-size="auto" -->



## Drifter applications

- Mapping surface currents:
  - Weather forecasting
  - Search and rescue operations
  - Calibrating coastal radar and satellite estimates of surface currents
- Measuring diffusion and dispersion
  - Tracking oil spills
  - Finding debris collection points (e.g., plastic)
  - Observing transport on scales too small to model



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/Capture1.PNG" data-background-size="auto" -->



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/Capture.PNG" data-background-size="auto" -->



# Overview

- Mostly off the shelf hardware, except conductivity
- In field tracking software
- Networked RF communication
- Temperature and conductivity logging
- Post-field visualization software
- Local applications



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/pybv10b-pinout.jpg" data-background-size="auto" -->



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/xbee-s2c-digimesh-2-4.jpg" data-background-size="auto" -->



## XBee Digimesh radios

- “Transparent” and API mode.  Transparent = imaginary RS232 cable
- More packet / routing control in API mode
- Sending JSON payloads, good for adding information en route.
- With six drifters, bandwidth not limiting.  RTS/CTS may be helping.



<!-- .slide: data-state="hide-head" -->
<!-- .slide: data-background="img/746-08.jpg" data-background-size="auto" -->



## Hardware

## Field software

## Post-field software



# Comms.

- RF ~500 m base to drifter
- ~300 m drifter to drifter?
- 1 km + with networking
- cellular?
- satellite?
- smart network?



# Smart network

- each drifter notes the last msg. from other drifters
- periodically or on demand, re-sends to base

# Battery life

- always on, 10+ hours
- sleep mode - days - weeks?
- sleeping makes comms. harder



# Local applications

- testing the FVCOM estuary model :-)
- fine scale movement, contaminant transport
- conductivity - trib. inputs (road salt)
- Apostles / Chequamegon Bay



# Future

- Stream “tumbler”?
- Outreach - students follow drifter around estuary in kayaks?


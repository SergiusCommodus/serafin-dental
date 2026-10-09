# Serafin Dentistry

Website for Serafin Dentistry, the dental practice of Dr. Caitlyn Serafin, DMD (Temple University, Maurice H. Kornberg School of Dentistry).

## What's here
- `index.html`: the full site (single page, no build step)
- `img/`: photos used on the site
- `audio/theme.mp3`: intro music that starts when a visitor taps "Enter site"

## Features
- Animated intro with a white tooth on a blue background and an Enter button that starts the music
- Services, first visit timeline, doctor bio, our story and clinic gallery
- Three step appointment request (visit type, calendar with time slots, details)
- Patient portal with a sign in screen and an interactive demo dashboard

## Run locally
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

## Notes
- The booking form and portal sign in do not send data anywhere yet. Connect them to the office's scheduling and practice software before launch.
- Get written photo releases from any patients shown before the site goes public.

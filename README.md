
# Prebuilt Birdseye Frontend Distribution

In case you don't want to build the frontend yourself,
e.g. you don't want to install npm, gulp and tons of JS dependencies,
you can find the prebuilt UI here.


## Installation

In your birdseye application directory (e.g. `/opt/ecix/birdseye/`)
just type

    ./bin/fetch_ui_dist


This is usually done by the startup script `start_uwsgi`.
However, you can disable auto downloading by setting `autodownload_ui = false`
in your `/etc/birdseye/birdseye.conf`



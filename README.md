# OpenGamepadUI session

This project is not affiliated with Valve (wide inspiration was taken from
their work on the SteamDeck). This configuration depends on [gamescope-session](https://raw.githubusercontent.com/ChimeraOS/gamescope-session)
from the ChimeraOS project.

## Basic manual setup

Copy this repository file structure into the appropriate places and you'll be
able to start the session on any Display Manager of your choice.

# Configuration

The session sources environment from `~/.config/environment.d/*.conf` files.
The easiest way to configure the session is to create `~/.config/environment.d/gamescope-session.conf`
and set variables there:

```
# Override entire OpenGamepadUI command line
CLIENTCMD="opengamepadui --only-qam"

# Override the entire Gamescope command line
# This will not use screen and render sizes
GAMESCOPECMD="gamescope -e -f"
```

# License & Contributing

The project is licensed under GPL v3 license. If you want to contribute,
just do so and thank you.

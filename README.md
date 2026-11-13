# PORTAL releases

This repo holds only built `.deb` packages for [PORTAL](https://github.com/Abuu20/portal) — no source
code. PORTAL's source lives in a private repo; this one exists purely so the install/update command
below can work without any authentication.

## Install / update

    curl -fsSL https://raw.githubusercontent.com/Abuu20/portal-releases/main/install.sh | sudo bash

Once PORTAL is installed, `portal --update` runs the same thing for you.

Every push to `main` in the private source repo builds a fresh `.deb` and publishes it here as a
rolling release called `latest`.

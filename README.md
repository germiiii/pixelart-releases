# PixelArt firmware releases

Signed firmware for PixelArt LED walls. Walls check
`<channel>/manifest.json` here every few hours and install newer releases
by themselves.

Every image is signed. A wall installs only firmware whose manifest verifies
against the public key built into it, and whose contents match the signed hash.
A file changed here, or anywhere between here and the wall, is rejected.

Published automatically. Don't edit by hand.

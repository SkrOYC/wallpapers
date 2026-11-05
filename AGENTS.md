# Brave New Tab Page wallpapers

Copy photographer backgrounds from the Brave New Tab Page (NTP) background images component. The files are not in `~/.cache`.

Use the highest `1.0.*` directory under:

`~/.config/BraveSoftware/Brave-Browser/aoojcmojmmcbpfgoecoadbdpnagfchel/`

The `photo.json` file maps each JPEG file (`source`) to an author and a campaign ID, such as `ntp-2026-Q4-17`.

An earlier set can remain under another profile, for example `Profile 8`. Prefer the highest version in the browser directory.

Skip any other component whose `photo.json` file contains `campaignId` or `logo`. Those entries are ads.

If a `source` filename is already in this repository and the bytes differ, rename the saved file to a descriptive slug. Then copy the component file under the photographer filename.

# K-Dash

Desktop software for aluminium composite panel distributors and manufacturers.
It reads the books you already keep in Tally, or from a file you export, and
answers the questions a day in that trade actually asks.

## Downloads

Every build is published under [Releases](../../releases). Download the
`K-Dash-Setup` file from the newest one and run it. If K-Dash is already
installed, run the new installer over the top — your book, your backups and
everything you have taught the app are kept. **Do not uninstall first.**

Windows will warn about an unrecognised publisher. The installer is not
code-signed yet, so that warning is expected.

## Licensing

The app installs and opens on the free plan. The other screens name the plan
they belong to and open when a licence key is entered under **Settings → Your
plan**.

## What is in this repository

Built installers and their signed manifests. Nothing else — the source is not
public. `manifest.json` is signed, and the app refuses any download whose
checksum does not match what that signed file says, so a tampered installer is
rejected by the app rather than trusted because of where it was downloaded
from.

---

*This page is a placeholder written by the build process. Proper copy is being
written separately.*

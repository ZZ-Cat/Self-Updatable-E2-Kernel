# Errata - A list of bugs, bombs, glitches & broken code.
This sheet contains a list of known bugs that exist in a given version of this software, plus temporary workarounds (if possible) until the bugs are fixed.

## Errata Summary.
| Errata Description | Affected Versions | Workaround(s) | Status |
|--------------------|-------------------|---------------|--------|
| Double initialization may be observed when the E2 is duplicated. | 1.0.0 to 1.2.1 | Adjust the reset-on-dupefinished delay to at least 500 mS. | Ongoing investigation. |
| Repeated infinite updates to User App, when the User App is automatically updated. | 0.1.0-a0.3.0 to 0.1.0-a0.3.1 | Wait for the first round of the automatic update to pass, then delete-&-respawn the kernel E2. | Fixed in version 1.0.0 |

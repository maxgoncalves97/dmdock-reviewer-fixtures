# DM Dock - synthetic certification test files

For **CC Desktop Preview**, DM Dock application `0.1.0-preview.11`, Store package
`1.0.13.0`, Windows 11 24H2/build 26100+ x64. No application login or private
GitHub access is required. Support: **DM Dock Support - dmdock.help@gmail.com**.

These are generated demonstration records, a quiet two-second tone and a
one-pixel white image. No real campaign or original user media is supplied.
This folder contains no installer, executable, script or application source.
The white image tests decoding/presentation; it is not a detailed map.

## Start with an independent test workspace

1. Install the certified **CC Desktop Preview** from Microsoft Store when it is
   available to your approved reviewer account. Do not sideload an unsigned MSIX.
2. Download/extract this entire reviewer folder to a normal local directory.
   Keep `synthetic-campaign/manifest.json` and its `payload/` together. Check the
   SHA-256 values in `SHA256SUMS.txt` using your normal verification tool.
3. Launch **DM Dock**. Select **Browse verified export**.
4. Select the **synthetic-campaign** directory, containing `manifest.json` and
   `payload`. Do not select `payload` or the outer reviewer folder.
5. Approve the independent workspace copy. The application verifies all 17
   payload files and creates an independent recovery copy. Do not select or
   replace an existing real campaign.
6. Select **Retry**, then verify that the campaign loads.
7. Open **Session Planner** and **Current Session**: choose **The Lantern Road -
   demo session**, with **Arrival at the gate** and **The lantern room** scenes.
   Open **NPCs**, **Quests** and **Encounters**. Expected synthetic examples are
   **Test Keeper**, **Test Adventurer**, **Find the lantern** and **Synthetic
   encounter**. DM-only example text must stay out of player-facing content.

This startup/import route was exercised in the extracted candidate, with native
folder-picker selections simulated. Genuine Store-installed acceptance, native
picker interaction and physical second-monitor behavior have not yet been tested.
If a previous preview workspace already opens, do not reset or overwrite it;
contact support for the supported independent test setup.

## Reconnect the supplied image, then test media

8. Open **Image Library -> Manage Library -> Advanced source settings**. In the
   existing **media** source row select **Reconnect artwork directory** and choose
   this package's **reviewer-media** directory. This retains the registered image
   ID. Do not use **Reconnect saved folders**, which is a different production
   connection workflow, or import a duplicate image.
9. Confirm **test-art.png** appears. It is intentionally a white pixel. Compare
   its size/hash with `reviewer-media/MEDIA.json`. Use **Present** and **Blackout**,
   and check the docked player preview. Where a player display is available,
   open it through the existing **Start Player Display** action.
10. In **Soundboard**, play/pause/stop **Synthetic tone**, starting at low speaker
    volume. Its bytes are already inside the campaign export; no audio folder
    reconnection or download is needed. The prepared scenes link the same track.

No video fixture is included or needed for this minimal test package. Separate
extracted-candidate regression tests covered MP4/WebM and animated dungeon media;
that does not claim video coverage through these supplied files.

The export's legacy format label `noxumbra-private`, relative `.local` paths and
two encounter `recovery` records are part of this exact synthetic export format,
not a production campaign, device identity or real recovery data. Keep the
export unchanged; `SHA256SUMS.txt` covers every file except itself.

Redistribution permission is in `LICENSE.txt`. No application rights are granted.

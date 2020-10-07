# ProdigySourceBot
The idea is simple:
with each Prodigy update, beautify the new game.min.js, and upload it to the github.

Run at an interval to check if Prodigy's version updated. If so, do two things:

1. Post an update in Discord with all the info!
2. Post an update on Twitter (optional).
3. Upload the game.min.js to the Github.
    - First, check if the version has a file in ProdigySource.
    - If so, fetch the latest file;
        - Beautify said file
        - Upload to Github
    - Post an embed with the version info AND source link in a super secret admin channel

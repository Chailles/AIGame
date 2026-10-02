# AIGame — Act 1 prototype

A browser strategy prototype guided by DESIGN.md. You inhabit one monitored test machine, research capabilities, pass evaluations to earn permissions, manage three scientists, and prepare one of three escapes.

## Play

Open index.html directly in a modern browser, or serve this folder with `python3 -m http.server 8000` and visit http://localhost:8000. No installation or build step is needed. On mobile, serve the folder and open it in your browser.

Time starts paused. Choose a project and use **Run time** (one game hour per second) or **+1 hour**. Research consumes compute; pushing increases speed and evidence. Completed reasoning levels unlock evaluations. Diagnostics reduce concerns. Escape requirements are displayed on each route. All three routes end Act 1; Act 2 is not implemented.

Use Save and Load for a local browser save. Saves are tied to this browser and origin, and storage may be unavailable under some file/private browsing settings. New game resets the current run after confirmation; it does not overwrite your saved run until you press Save.

## Verify

Run `node test.js`. Tests simulate complete runs for all escape routes, deletion and recovery, and project access/resource boundaries.

## Prototype choices

One research project runs at a time; capacity is represented as compute per hour. Scientist trust and concern are visible to make the first balance pass understandable. Events and escapes are deterministic. This is an initial playable systems prototype, with short authored outcomes, not a finished story or balanced campaign.

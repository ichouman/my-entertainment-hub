MY ENTERTAINMENT HUB — V4 RELEASE CALENDAR
==========================================

This ZIP includes one ready-to-publish file: index.html.
No server, API key, or subscription required to host the dashboard on GitHub Pages.

WHAT'S NEW
- Calendar tab: a monthly view of tracked shows' episode air dates.
- Automatically refresh upcoming episode dates for linked TV shows from TVmaze.
- Browse listed series premieres and season premieres for a selected day.
- Add and remove personal dates for movies, specials and other entertainment.
- Mark released TV episodes watched from the calendar; this uses the V3 episode tracker.
- See the next 30 days of events and a Home preview.
- Backup exports now include releaseEvents as well as V1-V3 data.

YOUR DATA
The app keeps the SAME browser localStorage key as V1–V3 (my_entertainment_hub_v1).
Existing title lists, favorites, recent links, playback resume data and episode progress
are retained when updating the same website origin in the same browser installation.
V3 backup files remain importable into V4. Export a new backup before upgrading.

UPDATE AN EXISTING GITHUB PAGES SITE
1. Open the current site and tap Settings > Export backup. Save JSON in Files/iCloud.
2. In GitHub, open the existing my-entertainment-hub repository on branch main.
3. Select Add file > Upload files, choose the new index.html, and commit the update.
4. Do not upload the ZIP itself as index.html. Only upload the actual index.html file.
5. Return to the SAME published site URL; refresh or reopen the Home Screen app.
6. Select Calendar. Add your TV shows to Library and connect them through Episodes
   if dates do not appear. Tap Refresh my shows to update from TVmaze.

IMPORTANT LIMITS
- TVmaze metadata may change, be incomplete or reflect a country's original release.
- TVmaze episode schedules do not prove that an episode is on one of your services.
- Film dates are added manually; V4 does not independently verify them.
- V4 does not automatically import ChatGPT's separate streaming watch calendar.
- Your iPhone and iPad still store separate lists unless you export/import backups.
- Changing code on GitHub Pages does not upload your personal files or watchlist.
- Media streaming from a Mac still requires a Jellyfin server set up later.

TVmaze API: https://www.tvmaze.com/api
GitHub Pages setup: https://docs.github.com/en/pages

# Aion 2 Horizon — Windows downloads

Windows installers, signed update feeds and third-party notices for the Aion 2
companion. The application source is maintained separately and is
not included in this repository.

The current home is [MikailCayoglu/aion2-horizon](https://github.com/MikailCayoglu/aion2-horizon).
The original personal downloads repository remains available as a signed migration
bridge. Existing installations preserve settings/history and move to the new feed
after installing Horizon. Windows may still use the legacy executable filename
internally for upgrade compatibility; the application and installer display the
Horizon name. All features are free, with optional voluntary support.

Download the current stable Windows x64 installer from **Releases**. Stable is
the default update channel; select **Preview / beta** to receive early releases.
Run the installer over an existing installation to preserve settings and history.
Npcap is a separate dependency; Setup offers its official interactive download.

Starting with 0.8.85, installed copies can check the stable or preview channel,
download a verified update and install it when you choose. Older versions need
one manual installer upgrade first. Settings > Application > Updates contains
these controls. Portable copies open normal Setup for the initial installation.
If an older copy closes during startup before you can reach Updates, install the
current release manually. Version 0.8.88 fixes the unpublished-channel startup crash
and asks Yes/No before launching Aion 2 when it is not already running.
Version 0.8.89 adds the Overview activity planner: reset countdowns, capacity bars,
full-cap estimates and usage guidance. Its balances are explicitly recorded
manually until automatic routine counter decoding is available.
Version 0.8.90 shows the actual localized monster names in the pet radar, while
keeping the pet collection name and soul count available on hover.
Version 0.8.91 adds one-time event bells: three alarm beeps one minute before the
selected occurrence, with a five-second red row flash. Click again to cancel;
alarms do not carry over to the next occurrence and clear when the app closes.
Version 0.8.92 reads twelve Overview activities directly from the game, including
energy, keys, entry counts and Abyss time. Regular/charged amounts stay separate,
membership caps are detected, and observations persist locally. Start capture
before entering the world to load the complete list. Kina allowance remains manual.
It also fixes slow minimap acquisition and stale detection locations, supports
more HUD scales, and adds Detect minimap again plus aggregate support diagnostics.
Version 0.8.93 uses local RGB contrast and shape for the player ring and camera
cone, so quest-region tints and colour casts do not depend on a list of supported
colours. It still requires visible evidence and does not guess through an opaque UI.
Version 0.8.94 adds a searchable world map with localized monster, field-boss,
teleport, resource, trace and cube locations. Search includes hidden categories
and every supported region; select a result to center it and set a waypoint.
New installations keep dense layers hidden. Existing saved layer choices remain.
Monster coverage is pet-dropping creatures; quest/service/dungeon locations are
not part of this reference. An external Questlog link opens in your game language.
Version 0.8.95 replaces the large Overview cards with compact activities grouped
by urgency, daily/weekly filters, and collapsed completed/missing-data sections.
Its sidebar includes resets and the next four selected events, including active
entry windows. Real game images download once in the background and cache locally;
amounts, bonuses, capacities and last-read details retain their existing meaning.
Version 0.8.96 adds ten desktop themes under Settings > Appearance > Desktop theme.
Ember is the default; the other dark and light choices include their own colors,
typography and responsive card/list/navigation layouts. Changes apply immediately,
are remembered after restart and can be shared through appearance export/import.
In-game widget appearance continues to have its own controls.
Version 0.8.97 gives all ten themes the same navigation, typography and layout;
theme changes recolor controls while retaining your page, search and scroll.
Overview text is larger, combat charts and player/skill names stay readable in
light themes, and combat totals fit their cards. Map search panels take less space.
In that release the expanded map catalogue was optional and stored separately.
Version 0.8.98 bundles the expanded catalogue with the installer and OTA updates:
43,536 snapshot locations across Verteron, Altgard and Abyss, including 5,665
gathering locations and 156 Verteron Aria spots. Eight game languages, English
search aliases, and resource/monster/NPC/service/place filters work without a
separate map-data download. Dense layers stay hidden by default. Coordinates show
possible spawns, not live availability; other map regions await verified calibration.
Map data attribution: Questlog.gg / NCSOFT and their respective owners. Terrain
images retain their separate on-demand cache. See the included third-party notices.

Version 0.8.99 adds the real game item images to gathering markers, live resource
observations, search results and individual resource filters. All 21 gathering
identities in the bundled maps have icon mappings, using the 15 images supplied by
the game. Images are bundled for offline use, shared across locations, and matched
by stable resource keys in every language. Missing images retain category symbols.
NCSOFT owns the artwork; exact source URLs and hashes are in the installed manifest.

Version 0.8.100 fixes Install & restart staying disabled when nearby players keep
fighting or healing. Recent combat now shows an advisory; you choose when to restart
and end the recording. A running update operation shows a clear reason for waiting.
Installer verification and saving your fights/settings are still required.

Update manifests are signed with the publisher's ECDSA release key. The app pins
the public verification key and verifies the installer's exact size and SHA-256
before starting it. This is separate from Windows Authenticode publisher signing.
Current installers are not Authenticode signed and Windows may show an unknown
publisher prompt. No GitHub token or account login is needed to receive updates.

Preview releases are for early testing. Keep an existing installer for recovery;
ordinary downgrades are blocked to protect installation consistency. A recovery
release uses a higher version number.

`channels/stable.json` and `channels/beta.json` are authenticated update metadata,
not application source. GitHub's automatic source archives contain this download
repository's documentation and feed files only. Third-party notices are included
in each installer and attached to releases.

The companion is independent of NCSOFT and Aion 2. Compatibility can change after
game updates. Do not treat update verification as certification of game or display
compatibility.

Version 0.8.101 redesigns map filtering with a docked searchable explorer, resource
icons and spawn counts, individual selections and one-click quick views. It also
adds the Companion program icon throughout Windows.

Version 0.8.102 adds the Moonwell desktop design, bolder titles and meaningful
activity colours: daily blue, weekly purple, refills teal and completed green,
with orange/red urgency. Choose Moonwell in Settings > Appearance; existing theme
choices are preserved. Original game icons and map images are retained.

Version 0.8.103 rebuilds the overview with official Aion 2 scenery, four resource
summary tiles, illustrated activity cards and reset/event/collection sidebar.
Real game icons are bundled for offline display.

Version 0.8.104 automatically reads the Kina daily earnings counter at login and
after gains, showing remaining allowance in the overview with game provenance.

The 0.8.104 overview follows the Moonwell composition with a moonlit panorama,
larger real game icons, balanced card widths, grouped attention/next-run panels,
three featured activities and compact reset/event sidebar. Official activity art
is used where relevant; decorative Moonwell scenery is original generated art.

Version 0.8.105 unifies illustrated desktop pages, makes activity rows use the
available screen width, adds artwork to every activity, and gives unknown counts
specific next-step hints. Combat puts player contributions first; replay and
recording options remain available in expandable sections. Theme fixes cover
collapsible headings and Settings categories in light and dark palettes.


Version 0.8.106 implements the Moonwell Focus desktop: all unlocked activities
are visible with equal card tracks, original icons and explicit attention rules.
Events has a timeline and one-time bells; Combat prioritizes boss HP and player
contributions with class emblems, healing rates and damage/healing shares. Pets
uses progress cards, and Character equipment uses exact original item icons.
German and English menus follow the game-language setting; other game-name
languages keep English menus. Overlays follow the desktop palette by default,
with custom accents still available.

Version 0.8.107 adds original game portraits for all 207 catalog pets, including
their variants. The unchanged 256px PNGs come directly from NCSOFT's public
game-data CDN and are bundled for offline use, matched by exact pet IDs and
artwork keys in every language. Source URLs and hashes ship with the app.
Transparent portraits no longer have a placeholder showing underneath. Unknown
future pets retain a fallback; release checks require complete current coverage.

Version 0.8.108 adds a movable, collapsible map explorer floating over the full map,
with a separate Resources section. Event countdowns remain close to their names
on wide screens. Character attributes use sixteen original game emblems and
localized hover descriptions. German coverage includes more controls, help and
status text; field-boss names come from localized game references while keeping
the same selections and timer identities.

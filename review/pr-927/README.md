# PR #927 visual evidence

Reviewed on 2026-10-19. These are proportionally downscaled copies, at most 1700px in either dimension.

HomeAssistant images: output commit 9b6bce1bbfabebeac77ee2d7bd3233425ba09114 from preview run 39172442596, source commit 8097ec59ab675e4fea40badee49a5cdd3c75f714.
Classic baseline images: output commit 5d1a281b1f7eee2757964a9c37ada7cf04f06c49, source baseline fcdd86e3. Classic previews are reported unchanged in the latest render comparison.

The new Home Assistant style is selectable alongside Classic. Classic is still the default. Light/dark showcase, dials and other cards were inspected. The thermostat ring has the expected scaled thickness and a visible white target handle. No clipped labels or controls were observed in these fixtures.

The preview tool ignores device dpi=160 (SCH-21), so original CI output exceeded 1800px; the review copies here meet the image limit. MainActivity synthetic preview output is missing (SCH-36), and the accessibility report has no fresh comparison because TV ATF fetches failed (SCH-37). No full accessibility pass is claimed.

Hive session: https://hive.codes/?session=session-1792237664402-be1403

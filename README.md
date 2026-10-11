# Bodycam Reforger

![Bodycam Reforger](images/preview.png)

**Bodycam-style weapon handling for Arma Reforger multiplayer.** Your weapon is carried, not glued to the mouse: every
small arm sways, kicks and settles like a real weapon in real hands. Camera, movement, controls, menus and all vehicles
stay Arma's.

**[Get it on the Arma Reforger Workshop](https://reforger.armaplatform.com/workshop/F26C9CD1DDF4D30E-BodycamReforger)**
– in game: Workshop → search "Bodycam Reforger" → subscribe. Servers list it like any other mod (mod ID
`F26C9CD1DDF4D30E`); players download it automatically. Version **1.3.0**.

## Weapon handling

- **Sway** – turning, walking, strafing and leaning move the weapon in your hands; it lowers on fast turns. Separate
  behaviour from the hip and aimed.
- **Recoil per weapon class** – rifles, machine guns, DMRs, pistols, SMGs, shotguns and bolt-action rifles – with a spray
  pattern: each shot moves your real aim, and it settles back after the burst. Launchers keep Arma's recoil.
- **Weapon physics** – the kick follows the bullet and the weapon's weight; heavy weapons sway slower. Suppressors and
  muzzle brakes take some of the kick.
- **Posture** – crouched, prone, rested on cover or on the bipod the weapon sways and kicks less.
- Iron sights and red dots stay usable; magnified optics keep Arma's view. A small camera kick per shot.

## Body

![Canting](images/canting.jpg)

- **Canting** – `Alt + Mouse 4` / `Alt + Mouse 5` tilts the weapon 30° to the left / right (the same key again levels it).
  Weapon and view move out to that side: together with the lean you see and shoot around corners earlier.
- **Hold breath** – hold `Shift` while aiming: steadier for about 6 seconds (shorter when out of breath), then a short,
  shaky exhale.
- **Arm fatigue** – long aiming makes the weapon unsteady and it sinks; much later when crouched, prone or rested.
- **Tremor and hits** – out of breath or with a wounded arm your hands tremble; a hit knocks the weapon away; raised to
  the eye, the weapon settles into the shoulder.
- All keys: Settings → Controls → "Bodycam Reforger".

## Server settings for admins

![Admin settings](images/admin_settings.jpg)

Pause menu → **Bodycam Reforger** (right under Settings):

| Setting | Range |
|---|---|
| Weapon sway (all), when turning, when walking | 0–200 % |
| **Bodycam recoil** – Off = Arma's complete original recoil (sway and the rest stay) | On / Off |
| Recoil kick, recoil climb, weapon physics, posture and rest | 0–200 % |
| Cant angle | 0–45° |
| Hold-breath time, exhale, arm fatigue, tremor, hit reaction, settling | 0–200 % |

0 % switches a feature off. The host, logged-in server admins and session admins can change the values; the server keeps
them in its profile folder (`bcr/settings.txt`, also editable there) and sends them to every player – also to players who
join later. Everyone else sees them read-only.

## Multiplayer

- Hit registration stays Arma's: bullets leave exactly where your barrel points, on the server too. Tested on a dedicated
  server: every shot of a burst leaves the same way on the server as on the shooter's PC – with our recoil and with Arma's.
- The weapon motion runs only on the shooter's PC; the server just keeps and sends the settings. Other players see your
  weapon without the sway.

## Compatibility

- Works for weapons built on Arma's weapon base classes, including many Workshop weapons. Weapon packs with their own
  base classes keep their own handling.
- Other weapon sway or recoil mods stack with this one – not recommended together.
- Vehicles, turrets and mounted weapons are not touched.

## Deutsch

Waffenhandling im Bodycam-Stil für Arma Reforger Multiplayer: Schwanken, Rückstoß pro Waffenklasse (abhängig von Geschoss,
Gewicht, Schalldämpfer und Mündungsbremse), Haltung und Zweibein, Kanten (`Alt + Maus 4/5`), Atem anhalten (`Shift`),
Arm-Ermüdung, Zittern und Treffer-Reaktion. Admins stellen im Pausemenü unter „Bodycam Reforger“ jede Wirkung für alle
Spieler ein; der Schalter „Bodycam recoil“ schaltet auf Armas originalen Rückstoß zurück. Die Trefferabfrage bleibt Armas –
die Kugeln gehen genau dahin, wo dein Lauf zeigt, auch auf dem Server. Mod im Spiel unter **Workshop → „Bodycam Reforger“**.

## License

© 2026 VAST-ON-GIT-OPENSOURCE. The mod "Bodycam Reforger", this page, its texts and images: **all rights reserved** –
no reuploads, edits or redistribution.

Not affiliated with Reissad Studio (BODYCAM) or Bohemia Interactive (Arma Reforger). Contains no BODYCAM files or content.

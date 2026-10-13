# Bodycam Reforger

![Bodycam Reforger](images/preview.png)

**Bodycam-style weapon handling for Arma Reforger multiplayer.** Your weapon is carried, not glued to the mouse: every
small arm sways, kicks and settles like a real weapon in real hands. Camera, movement, controls, menus and all vehicles
stay Arma's.

**[Get it on the Arma Reforger Workshop](https://reforger.armaplatform.com/workshop/F26C9CD1DDF4D30E-BodycamReforger)**
– in game: Workshop → search "Bodycam Reforger" → subscribe. Servers list it like any other mod (mod ID
`F26C9CD1DDF4D30E`); players download it automatically. Version **1.4.4** – the keyboard and mouse keys work again
(in 1.4.1–1.4.3 only the controller keys did).

## Weapon handling

- **Sway** – turning, walking, strafing and leaning move the weapon in your hands; it lowers on fast turns. Separate
  behaviour from the hip and aimed.
- **Recoil per weapon class** – rifles, machine guns, DMRs, pistols, SMGs, shotguns and bolt-action rifles – with a spray
  pattern: each shot moves your real aim, and it settles back after the burst. Launchers keep Arma's recoil.
- **Weapon physics** – the kick follows the bullet and the weapon's total weight with every attachment and the magazine:
  a scope, launcher or suppressor makes it steadier, also on Workshop weapons. Suppressors, muzzle brakes, compensators
  and foregrips take some of the kick.
- **Posture** – crouched or prone the weapon sways and kicks less; rested on cover or on the bipod it stays almost still,
  so scoped bursts stay on target.
- Iron sights and red dots stay usable; magnified optics keep Arma's view. A small camera kick per shot.

## Poses – every player sees them

| Pose | Keyboard | Controller | |
|---|---|---|---|
| **High ready** | `Ctrl + Mouse 5` | `RB + R3` | muzzle up in front of the chest, both hands on the weapon; the trigger brings it down first |
| **Low ready** | `Ctrl + Mouse 4` | `RB + L3` | Arma's own lowered weapon, also while sprinting |
| **Blind fire** | `Ctrl + X` | `RB + Y` | weapon over the head, the muzzle lifts clear of a parapet edge; leaning (`Q` / `E`, controller: hold `A` + left stick) takes it round the left / right corner |
| **Blind fire round a corner** | `Shift + Mouse 5` / `Shift + Mouse 4` | `RB + D-pad left` / `RB + D-pad right` | weapon across the chest, muzzle out to the left / right, body behind the wall; to the right (arms crossed) far less accurate; beside a wall it stays back and holds fire |
| **Point shooting** | `Ctrl + Middle mouse` | `RB + A` | canted at the hip for quick close shots – to the right, with the left cant key to the left |
| **Canted carry** | `Alt + Middle mouse` | `RB + View` | the weapon tilted far to the left (with the right cant key to the right), low in view, to walk with |

**Poses and the cant combine.** Lean in any pose, also with a part lean (`Ctrl + Q` / `Ctrl + E`) – poses keep their
place; blind fire + lean takes the weapon round the corner; cant + lean the same way reaches further. The cant keys pick
the side of point shooting and the canted carry (started while canted, they take that side) and end high / low ready and
blind fire. The same key ends a pose, aiming down the sights ends any pose. Admins can switch blind fire off for the
whole server.

## Body

![Canting](images/canting.jpg)

- **Canting** – `Alt + Mouse 5` / `Alt + Mouse 4` (controller `RB + X` / `RB + B`) tilts the weapon 30° to the left / right (the same key again levels it).
  Weapon and view move out to that side; canted and leaning the same way you reach 9 cm further round the corner, from
  the hip and aimed. Every player sees your cant.
- **Hold breath** – hold `Shift` (controller: hold `A`) while aiming: steadier for about 6 seconds (shorter when out of breath), then a short,
  shaky exhale.
- **Arm fatigue** – long aiming makes the weapon unsteady and it sinks; much later when crouched, prone or rested.
- **Tremor and hits** – out of breath or with a wounded arm your hands tremble; a hit jolts your aim off target; raised
  to the eye, the weapon settles into the shoulder.

## Controls – keyboard and controller

Every key has a keyboard and a controller default. On a controller (Arma's standard controller layout) `RB` is the
modifier, like Arma's own zoom (`RB + D-pad up / down`); sprint, radio, aiming and firing stay free. Each player rebinds
every key in **Settings → Controls → "Bodycam Reforger"** (keyboard and controller column) – no admin rights needed.
The admin settings page works with a controller too. Every key is checked with real key presses before a release.

## Server settings for admins

![Admin settings](images/admin_settings.jpg)

Pause menu → **Bodycam Reforger** (right under Settings, also with a controller):

| Setting | Range |
|---|---|
| Weapon sway (all), when turning, when walking | 0–200 % |
| **Bodycam recoil** – Off = Arma's complete original recoil (sway and the rest stay) | On / Off |
| Recoil kick, recoil climb, weapon physics, posture and rest | 0–200 % |
| Cant angle | 0–45° |
| **Blind fire allowed** – Off = no blind fire on the server | On / Off |
| Hold-breath time, exhale, arm fatigue, tremor, hit reaction, settling | 0–200 % |

0 % switches a feature off. Only the host and logged-in server admins (`#login`) can change the values – not a voted-in
session admin. The server keeps
them in its profile folder (`bcr/settings.txt`, also editable there) and sends them to every player – also to players who
join later. Everyone else sees them read-only.

## Multiplayer

- Hit registration stays Arma's: bullets leave exactly where your barrel points, on the server too. Tested on a dedicated
  server with two players: every shot of a burst leaves the same way on the server as on the shooter's PC – with our
  recoil, with Arma's and in blind fire.
- Poses and canting go to every player, also to players joining later. The sway runs only on the shooter's PC; the
  server keeps the settings and the pose of each soldier.

## Compatibility

- Works for weapons built on Arma's weapon base classes, including many Workshop weapons and their attachments. Weapon
  packs with their own base classes keep their own handling.
- Other weapon sway, recoil or pose mods stack with this one – not recommended together.
- Vehicles, turrets and mounted weapons are not touched.

## Deutsch

Waffenhandling im Bodycam-Stil für Arma Reforger Multiplayer: Schwanken, Rückstoß pro Waffenklasse (abhängig von Geschoss
und Gesamtgewicht mit allen Anbauteilen; Schalldämpfer, Mündungsbremse, Kompensator und Griff nehmen Rückstoß), Haltung,
aufgelegt und Zweibein fast ruhig. Posen, für alle Spieler sichtbar: High Ready (`Strg + Maus 5`), Low Ready
(`Strg + Maus 4`), Blind Fire (`Strg + X`, mit `Q` / `E` um die Ecke), Point Shooting (`Strg + mittlere Maustaste`),
Blind Fire um die Ecke ohne Lehnen (`Shift + Maus 5 / 4`) und schräge Trageweise (`Alt + mittlere Maustaste`). Posen und
Kanten sind kombinierbar: Lehnen in jeder Pose, die Kanten-Tasten wählen die Seite von Point Shooting und schräger
Trageweise. Controller-Unterstützung – jede Taste hat eine Controller-Belegung (RB als Umschalter, z. B. `RB + X` /
`RB + B` Kanten, `RB + Y` Blind Fire, `A` halten beim Zielen = Atem anhalten); jeder Spieler belegt alle Tasten selbst um
unter Einstellungen → Steuerung → „Bodycam Reforger“. Neu in 1.4.4: die Tastatur- und Maus-Tasten gehen wieder (in
1.4.1–1.4.3 ging nur der Controller).
Kanten (`Alt + Maus 5 / 4`, mit Lehnen zur selben Seite 9 cm weiter um die Ecke), Atem anhalten (`Shift`), Arm-Ermüdung,
Zittern und Treffer-Reaktion. Admins stellen im Pausemenü unter „Bodycam Reforger“ jede Wirkung für alle Spieler ein;
„Bodycam recoil“ schaltet auf Armas originalen Rückstoß zurück, „Blind fire allowed“ schaltet Blind Fire ab. Die
Trefferabfrage bleibt Armas – die Kugeln gehen genau dahin, wo dein Lauf zeigt, auch auf dem Server und im Blind Fire.
Mod im Spiel unter **Workshop → „Bodycam Reforger“**.

## License

© 2026 VAST-ON-GIT-OPENSOURCE. The mod "Bodycam Reforger", this page, its texts and images: **all rights reserved** –
no reuploads, edits or redistribution.

Not affiliated with Reissad Studio (BODYCAM) or Bohemia Interactive (Arma Reforger). Contains no BODYCAM files or content.

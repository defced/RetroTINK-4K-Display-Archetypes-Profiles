# RetroTINK-4K-Display-Archetypes-Profiles
A personal collection of RetroTINK 4K Pro profiles designed to emulate a wide range of historical display technologies — from professional broadcast CRT monitors and consumer televisions to arcade cabinets, PC monitors, handheld screens, and early flat panels.

## Table of Contents

- [Philosophy](#philosophy)
- [How to Install](#how-to-install)
- [Required Setup](#required-setup)
- [Profiles](#profiles)
- [Links](#links)

### PRO SERIES
- [01 PRO - HD BVM 1000](#01-pro---hd-bvm-1000)
- [02 PRO - BVM 800](#02-pro---bvm-800)
- [03 PRO - PVM 600](#03-pro---pvm-600)
- [04 PRO - Shadow Mask](#04-pro---shadow-mask)
- [05 PRO - Arcade 90s](#05-pro---arcade-90s)
- [06 PRO - Arcade 80s](#06-pro---arcade-80s)
- [07 PRO - Medical Mono](#07-pro---medical-mono)
- [08 PRO - CCTV Mono](#08-pro---cctv-mono)

### TV SERIES
- [10 TV - HD CRT Widescreen 100Hz](#10-tv---hd-crt-widescreen-100hz)
- [11 TV - Trinitron](#11-tv---trinitron)
- [12 TV - Slot Mask (D-Series Style)](#12-tv---slot-mask-d-series-style)
- [13 TV - 90s Budget](#13-tv---90s-budget)
- [14 TV - 80s Budget](#14-tv---80s-budget)

### PC SERIES
- [20 PC - High-End CRT (FW900)](#20-pc---high-end-crt-fw900)
- [21 PC - VGA Pro (Iiyama VM)](#21-pc---vga-pro-iiyama-vm)
- [22 PC - 90s VGA Classic](#22-pc---90s-vga-classic)
- [23 PC - Mono Amber](#23-pc---mono-amber)
- [24 PC - Mono Green](#24-pc---mono-green)
- [25 PC - LCD Early 2000s TN](#25-pc---lcd-early-2000s-tn)
- [26 PC - LCD Late 2000s Studio IPS](#26-pc---lcd-late-2000s-studio-ips)

### HANDHELD SERIES
- [30 LCD - DMG](#30-lcd---dmg)
- [31 LCD - Grayscale](#31-lcd---grayscale)
- [32 LCD - Early Color](#32-lcd---early-color)
- [33 LCD - Triad Color](#33-lcd---triad-color)
- [34 LCD - Reflective Color](#34-lcd---reflective-color)
- [35 LCD - Backlit Color](#35-lcd---backlit-color)
- [36 OLED - Amoled](#36-oled---amoled)

### SPEC SERIES
- [40 SPEC Plasma - EDTV](#40-spec-plasma---edtv)
- [41 SPEC LCD - Early HD TV](#41-spec-lcd---early-hd-tv)
- [42 SPEC DLP - Projector](#42-spec-dlp---projector)
- [43 SPEC LED - Dot Matrix Panel](#43-spec-led---dot-matrix-panel)
- [44 SPEC CRT - Vector](#44-spec-crt---vector)
- [45 SPEC CRT - Micro Travel](#45-spec-crt---micro-travel)
- [46 SPEC LCD - Camera Screen](#46-spec-lcd---camera-screen)
- [47 SPEC DMD - Pinball Display](#47-spec-dmd---pinball-display)
- [48 SPEC LED - Virtual Boy](#48-spec-led---virtual-boy)

## PHILOSOPHY

These profiles are artistic recreations built from research, archival references, period photography, video documentation, and personal experience growing up with these displays throughout the 80s, 90s, and early 2000s.
They are not laboratory-calibrated reproductions. Instead, they aim to recreate the feeling, atmosphere, and visual identity of the original displays rather than strict scientific accuracy.

Due to technical limitations of the RetroTINK 4K (for example, the inability to reproduce LCD motion trailing), some characteristics cannot be perfectly replicated.

The goal of these profiles is to capture the spirit and personality of the original hardware as faithfully as possible within the capabilities of the device.


## HOW TO INSTALL

### Installing the profiles:
Copy the folder located inside the "profile" directory into the "profile" folder of your RetroTINK 4K SD card.

You may rename the profile folder if you want.

### Installing the required masks:
Copy the "defced_archetypes" folder into the "mask" folder of your RetroTINK 4K SD card.

Do not rename this folder, otherwise the profiles will not be able to locate and load the masks correctly.

The "Mono Masks" and "RGB Masks" folders contain masks used by some profiles, but these should already be included by default on the RetroTINK 4K.

If they are missing, simply copy both folders into the "mask" folder of the RetroTINK 4K SD card.


## REQUIRED SETUP

These profiles were created and tuned using a MiSTer FPGA connected to an LG C1 OLED in 4K HDR with Black Frame Insertion (BFI) enabled.

They should still work well on most OLED displays, but for the intended rendering, the following setup is recommended:

### MiSTer FPGA:
In mister.ini, set:
direct_video=1

This is highly recommended for optimal image quality and signal accuracy.

### TV Setup:
- Enable Game Mode or Game Optimizer
  (On LG TVs: All Settings → General → Game Optimizer)

- Enable Black Frame Insertion (BFI)
  (On LG TVs: set OLED Motion Pro to High)

- Disable VRR (Variable Refresh Rate)

These profiles are specifically optimized for HDR usage with BFI enabled, which significantly darkens the image.
If you are not using BFI, you can lower the SMPTE 2084 (PQ) value in the RT4K Color Correction menu to around 1000 nits for a more balanced brightness level.

All profiles were created and tested using RetroTINK 4K firmware version 1.9.6.

# Profiles

## PRO SERIES

Professional monitors and broadcast reference displays

---

### 01 PRO - HD BVM 1000

A late-generation HD broadcast CRT inspired by flagship studio BVM monitors.

Extremely sharp, clinically precise, with perfectly separated scanlines and virtually no softness.

Use this when you want your Xbox, PS2 or GameCube to feel wired into a professional mastering suite in the early 2000s — pure reference monitor energy.

---

### 02 PRO - BVM 800

A recreation of the classic 800 TVL broadcast BVM monitor look.

Pronounced, tightly spaced scanlines with high sharpness, minimal phosphor blending, and strong pixel separation.

Perfect for 16-bit and 32-bit consoles — the RGB reference look most collectors aspire to.

---

### 03 PRO - PVM 600

Inspired by 600 TVL Sony PVM monitors.

Moderate sharpness, natural scanlines, and gentle phosphor blending create a cohesive, authentic CRT image without the clinical edge of a BVM.

Perfect from 8-bit to PS2 — the true sweet spot for retro gaming, and the kind of professional CRT most enthusiasts actually dream of having in their game room.

---

### 04 PRO - Shadow Mask

Inspired by professional shadow-mask studio monitors often found in high-end JVC or Panasonic broadcast setups.

Softer beam structure, smoother color blending, and a more organic image compared to the razor-sharp precision of Sony's aperture grille displays.

Ideal when you want a studio-grade CRT with added warmth and texture — the kind of professional monitor that feels less clinical and more alive.

---

### 05 PRO - Arcade 90s

Captures the look of a 90s Japanese arcade cabinet monitor, inspired by Sega Astro City–style setups.

Slightly warm tones, bright phosphor glow, and bold contrast with a lively screen presence.

Perfect for fighting games, shoot ’em ups, and Neo Geo titles — like stepping into a crowded arcade in 1996, the hum of machines in the air and a line of coins waiting on the control panel.

---

### 06 PRO - Arcade 80s

Emulates the look of early-generation arcade CRT monitors from the golden age of the 1980s.

Bright primary colors, reduced sharpness, noticeable beam bloom, and lighter black levels typical of early arcade CRTs.

Perfect for 80s arcade classics like Donkey Kong and Pac-Man — back when attract screens blazed in the dark and arcade rooms echoed with buzzing speakers and coin drops.

---

### 07 PRO - Medical Mono

The look of a high-resolution monochrome medical imaging monitor.

Crisp grayscale rendering, sharp detail, and strong contrast without any color information — purely luminance-driven precision.

Perfect for survival horror or atmospheric titles — like viewing the game through a diagnostic display in a quiet hospital lab after hours.

---

### 08 PRO - CCTV Mono

Captures the look of a monochrome security surveillance monitor.

Cold blue-tinted monochrome tones, slightly lifted blacks, and muted contrast recreate the hazy, low-light feel of an old surveillance rack.

Hook up your Mega Drive like you’re killing time on a night shift, one eye on the cameras and the other on the screen — pure security-room atmosphere.


---

## TV SERIES

Consumer televisions

---

### 10 TV - HD CRT Widescreen 100Hz

A late-era widescreen HD CRT television with built-in digital processing.

Reduced flicker, softened scanline visibility, and a denser, more processed image create a stable presentation that almost resembles an early flat-screen display.

Ideal for revisiting the mid-2000s, when your PS2 or GameCube felt next-gen on a big 16:9 living room TV — modern, sharp, and just a little ahead of its time.

---

### 11 TV - Trinitron

The iconic Sony consumer Trinitron television look.

Vivid phosphors, strong contrast, visible aperture-grille structure, and that distinctive Sony color intensity — especially in reds and skin tones.

This is 90s gaming in the family living room — bright Saturday morning platformers, glowing PlayStation nights, and the TV everyone secretly knew was “the good one.”

---

### 12 TV - Slot Mask (D-Series Style)

A premium slot-mask CRT in the spirit of Panasonic and JVC — a genuine Trinitron alternative.

Smoother phosphor blending, balanced contrast, and a cohesive image structure without the pronounced sharpness of an aperture-grille display.

The kind of premium family TV that rivaled Sony — and quietly proved there was more than one way to achieve a great CRT image.

---

### 13 TV - 90s Budget

An entry-level early-90s television, reminiscent of Philips, Thomson, Grundig, or GoldStar sets found in countless bedrooms.

Softer focus, lighter blacks, and visible blur with gentle color bleed — less precision, more analog charm.

The bedroom TV most of us actually played on — sitting too close to the screen, Mega Drive plugged in so you wouldn’t monopolize the living room, gaming long past bedtime.

---

### 14 TV - 80s Budget

A compact 80s consumer CRT, reminiscent of small Philips, Thomson, or GoldStar sets found in modest living rooms.

Low perceived resolution, heavy phosphor blending, thick scanlines, and softer focus give the image a distinctly early-console character.

Boot up an NES title and you’re back in a small living room with wood furniture, patterned carpet, and a controller cable stretched tight across the floor.

---

## PC SERIES

Computer monitors and desktop display technologies

---

### 20 PC - High-End CRT (FW900)

An ultra high-end 16:10 widescreen CRT monitor inspired by flagship models like the Sony FW900.

Extremely fine pitch, high resolution, tight scanlines, and a dense, razor-sharp image with impressive brightness and depth.

Dreamcast in VGA. Early HD PC gaming. Once overlooked by most players, this is the kind of monitor retro enthusiasts rediscovered years later — realizing it was a hidden gem all along.

---

### 21 PC - VGA Pro (Iiyama VM)

Inspired by high-end Iiyama Vision Master Pro–style PC monitors.

Visible aperture-grille structure, precise RGB separation, and a sharp, stable desktop image with strong contrast and clarity.

Perfect for Windows 95, early 3D accelerators, and competitive late-90s PC gaming — the kind of monitor only demanding players and semi-pro setups invested in.

---

### 22 PC - 90s VGA Classic

A standard 90s VGA/SVGA desktop CRT monitor — the kind found on most home PCs.

Slight softness, visible scanlines at lower resolutions, gentle phosphor glow, and modest contrast typical of everyday VGA displays.

Perfect for DOS and early Windows 95 gaming — when getting a game to run was half the battle, shareware discs piled up next to the keyboard, and the modem’s handshake echoed through the room.

---

### 23 PC - Mono Amber

Emulates the look of an amber phosphor monochrome PC monitor common in the mid-to-late 1980s.

Warm amber glow, high-contrast text, and a crisp luminance-driven image with no color distraction.

Feels like writing code late at night in 1988 — a dark room, a blinking command prompt, and the quiet hum of a beige PC beside the desk.

---

### 24 PC - Mono Green

Emulates the look of a classic green phosphor monochrome monitor used on early IBM PCs and Apple II systems.

High-contrast green luminance, sharp text rendering, and a clean, utilitarian image focused purely on clarity.

Early computer labs, school classrooms, and the very beginning of home computing — when every command mattered and the future felt programmable.

---

### 25 PC - LCD Early 2000s TN

Emulates the look of an early 2000s TN-panel office LCD monitor.

Grayish blacks, limited contrast, and a clearly defined pixel grid give the image that unmistakable early flat-panel look.

Half-Life 2, Warcraft III, or The Sims running on a beige desktop PC in a shared family office — the era when LCDs felt futuristic, even if they weren’t perfect.

---

### 26 PC - LCD Late 2000s Studio IPS

The look of a late 2000s high-end IPS graphics monitor.

Accurate colors, wider viewing angles, improved contrast, and a smoother, more cohesive image compared to early TN panels.

The golden age of PC gaming — when Crysis pushed hardware to its limits and BioShock proved how atmospheric a game could look on a serious desktop display.

---

## HANDHELD SERIES

Portable gaming display technologies

---

### 30 LCD - DMG

Emulates the original passive-matrix Game Boy (DMG) screen.

Olive-green tint, low contrast, noticeable motion blur, and visible pixel persistence characteristic of early handheld LCD technology.

Perfect for Tetris, Super Mario Land, or Kirby’s Dream Land — and ideal for recreating the Gamate or Watara Supervision experience on MiSTer.

---

### 31 LCD - Grayscale

Emulates the look of passive-matrix grayscale handheld displays like the Game Boy Pocket.

Neutral gray tones, limited contrast, and subtle motion blur characteristic of late-90s monochrome LCD technology.

Perfect for quiet afternoon Pokémon sessions, imported WonderSwan titles, or early Neo Geo Pocket games — just before handheld gaming fully embraced color.

---

### 32 LCD - Early Color

Emulates the look of first-generation color handheld LCD screens like the Game Gear and Atari Lynx.

Oversaturated colors, limited contrast, visible pixel structure, and a slightly washed presentation typical of early handheld color LCD technology.

Perfect for recreating late-night sessions under the covers, console plugged into the wall, the bright screen glowing in the dark — early portable color gaming at its most intense.

---

### 33 LCD - Triad Color

Emulates the delta-triad TFT pixel structure found in high-end handhelds like the PC Engine GT / LT.

Clearly defined RGB subpixel layout, tighter pixel structure, and richer color rendering compared to earlier passive LCD screens.

Perfect for recreating the premium feel of the PC Engine GT — or imagining what Megadrive games might have looked like if the Nomad had shipped with a better display.

---

### 34 LCD - Reflective Color

Emulates the look of reflective color LCD screens without a backlight, as seen on the Game Boy Color and the first-generation Game Boy Advance.

Muted colors, limited contrast, and strong dependence on ambient light — the image only truly comes alive under bright conditions.

Perfect for recreating that era when handheld gaming meant chasing sunlight, and when the original GBA’s beautiful games were held back by a screen that desperately needed a backlight.

---

### 35 LCD - Backlit Color

Emulates the look of early backlit handheld LCD screens such as the Game Boy Advance SP (AGS-101) and similar early backlit handheld panels.

Brighter image with improved low-light visibility, yet still limited contrast, modest black depth, and the characteristic glow of early backlit LCD panels.

Perfect for reliving the spirit of those handheld classics — WonderSwan Color or GBA titles on MiSTer, captured with the feel of their original screens.

---

### 36 OLED - Amoled

Emulates the look of modern handheld OLED displays such as the PlayStation Vita (OLED model) and the Nintendo Switch OLED.

Deep blacks, vibrant colors, strong contrast, and a dense, punchy image with no backlight glow.

Perfect for imagining how your favorite retro games would look on a premium modern handheld — or for recreating the bold OLED presentation of Nintendo Classics on Switch.

---

## SPEC SERIES

Experimental and niche display simulations

---

### 40 SPEC Plasma - EDTV

Emulates the look of early plasma televisions from the mid-to-late 2000s.

Subtle dithering, phosphor-like glow, deep blacks, and a textured image that feels closer to CRT technology than early HD LCD panels.

Perfect for reliving the early HD era — Xbox 360 in 720p or PS3 in 1080p, when plasma was the best way to get truly deep blacks and a cinematic image in a modern flat-screen TV.

---

### 41 SPEC LCD - Early HD TV

The look of first-generation consumer HD LCD televisions from the mid-2000s.

Grayish blacks, uneven color balance, limited contrast, and early digital scaling artifacts define the image — sharp in resolution, but imperfect in tone.

The beginning of the HD era — when Xbox 360 and Gears of War felt like the future, even if the screen wasn’t quite ready for it.

---

### 42 SPEC DLP - Projector

Emulates the look of early consumer DLP projector setups from the mid-2000s.

Large projected image, slightly softened detail, visible digital texture, and a bright, cinematic presentation that favors scale over pixel precision.

Perfect for recreating mid-2000s weekend sessions — Halo multiplayer projected onto a wall, or 10-player Bomberman Saturn tournaments lighting up a living room like a mini gaming event.

---

### 43 SPEC LED - Dot Matrix Panel

Emulates the look of large LED dot-matrix displays commonly seen in stadium screens, public signage, and advertising panels.

Massive circular pixels, visible spacing between LEDs, and bright, highly saturated colors create a bold, larger-than-life image designed to be seen from far away.

Perfect for imagining what classic games might look like on a giant public display — 8-bit and 16-bit consoles blown up to stadium scale.

Note: this profile has been specifically tuned for Mega Drive output from MiSTer.

---

### 44 SPEC CRT - Vector

A vector-based CRT display in the style of the Vectrex and classic vector arcade machines.

Bright, razor-sharp lines drawn directly by the electron beam — no raster grid, no pixels, just pure luminous geometry against a dark screen.

Perfect for vector arcade classics in a dim room — a rare and almost otherworldly display style that still feels unlike anything else.

---

### 45 SPEC CRT - Micro Travel

A miniature CRT display inspired by tiny portable televisions like the Sony Watchman.

Very low perceived resolution, washed-out colors, visible scanlines, and exaggerated geometry create a compact, almost toy-like CRT presentation.

Like a pocket-sized TV from another era — impractical, charming, and somehow capable of running your 90s games in the most unexpected way.

---

### 46 SPEC LCD - Camera Screen

Inspired by the tiny early-2000s LCD preview screens found on compact digital cameras and camcorders, such as the Sony Mavica FD7.

Very low resolution, washed-out colors, limited viewing angles, and a flat, overly digital image typical of small camera displays of that era.

Like watching your retro game through the 2-inch screen on the back of a silver point-and-shoot — a strangely charming, unmistakably early-digital experience.

---

### 47 SPEC DMD - Pinball Display

Emulates the plasma dot-matrix displays used in 90s pinball machines.

Large circular pixels, strong contrast, and a warm amber glow recreate the distinctive look of classic pinball score displays.

Perfect for giving retro games the feel of a giant animated pinball display — especially fun with 8-bit titles and 80s arcade games.

---

### 43 SPEC LED - Virtual Boy

Emulates the distinctive red LED display of the Nintendo Virtual Boy.

Deep monochrome red tones, high contrast, and a dense pixel structure recreate the intense visual style of Nintendo’s experimental 3D console.

Perfect for exploring how classic games might look through the unmistakable red glow of the Virtual Boy — a bold and unusual display unlike anything else.

# Links

My website: https://www.cedricbarthez.fr


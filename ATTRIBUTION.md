# Attribution
## Collaborators

### Godot Game Template
![Maaack Plugin Icon](/assets/plugin_logo/logo.png)  
Author: [Marek Belski and contributors](https://github.com/Maaack/Godot-Game-Template/graphs/contributors)  
Source: [github: Godot-Game-Template](https://github.com/Maaack/Godot-Game-Template)  
License: [MIT License](LICENSE.txt)  

## Sourced
#### Background music — Rising Moon
Author: [RandomMind](https://opengameart.org/users/randommind)  
Source: [Fantasy: Rising Moon](https://opengameart.org/content/fantasy-rising-moon)  
License: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)  
File: `assets/audio/rising_moon.mp3`. The full original track is unchanged. Looping, fade-in and volume are applied at runtime.

#### Interface — Page Turn
Author: [qubodup](https://freesound.org/people/qubodup/)  
Source: [Page Turn, sound 442857](https://freesound.org/people/qubodup/sounds/442857/)  
License: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)  
File: `assets/audio/page_turn.wav`. Prepared from the source page's high-quality MP3 preview: PCM conversion, level adjustment and short edge fades. Duration: 0.581 seconds. The source is a remix of a CC0 recording by [Caitlin_100](https://freesound.org/people/Caitlin_100/sounds/365497/).

#### Interface — Basic Click Wooden
Author: [GameAudio](https://freesound.org/people/GameAudio/)  
Source: [Basic Click Wooden, sound 220200](https://freesound.org/people/GameAudio/sounds/220200/)  
License: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)  
File: `assets/audio/wooden_click.wav`. Prepared from the source page's high-quality MP3 preview: PCM conversion, level adjustment and short edge fades. Duration: 0.500 seconds.

#### Interface — Soft knocks on door
Author: [DrFahrts](https://freesound.org/people/DrFahrts/)  
Source: [Soft knocks on door, sound 635282](https://freesound.org/people/DrFahrts/sounds/635282/)  
License: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)  
File: `assets/audio/door_knock.wav`. Prepared from the source page's high-quality MP3 preview. The first three knocks are retained, using the 1.24–2.34 second interval of the 9.8 second recording; PCM conversion, level adjustment and short edge fades are applied. Final duration: 1.100 seconds.

Interface audio source files are preserved outside the exported game in `../Art/audio_sources/`. Preparation can be repeated with `tools/prepare_interface_audio.gd` using Godot; no external converter is required.

#### Cartographic illustrations
Author: [K. M. Alexander](https://kmalexander.com/)  
Source: [Mercator Settlement](https://kmalexander.com/2026/06/30/mercator-settlement-a-free-16th-century-settlement-brush-set-for-fantasy-maps/) and [Hogenburg](https://kmalexander.com/2024/08/27/hogenburg-a-free-16th-century-urban-cartography-brush-set-for-fantasy-city-maps/)  
License: [CC0](https://creativecommons.org/publicdomain/zero/1.0/)  
Original PNGs are unchanged. The screen applies an ink tint and slightly strengthens their opacity at runtime.

#### Interface borders
Author: [Kenney](https://kenney.nl/)  
Source: [Fantasy UI Borders](https://kenney.nl/assets/fantasy-ui-borders)  
License: [CC0](https://creativecommons.org/publicdomain/zero/1.0/)  
Original images are unchanged; colours and sizing are applied at runtime.

#### Resource icons
Icons made by [Lorc](https://lorcblog.blogspot.com) and [Delapouite](https://delapouite.com).  
Available on [Game-icons.net](https://game-icons.net).  
License: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)  
Original SVGs are unchanged. Their colour and size are changed at runtime.

#### Godot Engine Logo
Author: Andrea Calabró  
Source: [godotengine.org : press](https://godotengine.org/press/)  
License: [CC BY 4.0 International](https://github.com/godotengine/godot/blob/master/LOGO_LICENSE.txt) 

#### Git Logo
Author: [Jason Long](https://bsky.app/profile/jasonlong.me)  
Source: [git-scm.com : logos](https://git-scm.com/downloads/logos)  
License: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) 

## Tools
#### Godot
![Godot Engine Logo](/assets/godot_engine_logo/logo_vertical_color_dark.png)  
Author: [Juan Linietsky, Ariel Manzur, and contributors](https://godotengine.org/contact)  
Source: [godotengine.org](https://godotengine.org/)  
License: [MIT License](https://github.com/godotengine/godot/blob/master/LICENSE.txt)  

#### Visual Studio Code
Author: [Microsoft](https://opensource.microsoft.com/)  
Source: [github: vscode](https://github.com/microsoft/vscode)  
License: [MIT License](https://github.com/microsoft/vscode/blob/main/LICENSE.txt)

#### Git
![Git Logo](/assets/git_logo/Git-Logo-2Color.png)  
Author: [Linus Torvalds](https://github.com/torvalds)  
Source: [git-scm.com](https://git-scm.com/downloads)  
License: [GNU General Public License version 2](https://opensource.org/licenses/GPL-2.0)

## Browser typography

`assets/fonts/NotoSerif-Regular.ttf`, `NotoSans-Regular.ttf`, `NotoSansMath-Regular.ttf` and `NotoSansSymbols2-Regular.ttf` supply Cyrillic text, serif headings, mathematical signs and navigation symbols where Web builds cannot access system fonts. Symbols 2 alone does not cover arrows or the mathematical minus; the Math family completes the fallback chain. Source: [Noto fonts](https://github.com/notofonts/noto-fonts/tree/main/hinted/ttf). Copyright 2018 The Noto Project Authors. Distributed unmodified under SIL Open Font License 1.1; the complete license is included in `assets/fonts/OFL.txt` and browser distributions. Runtime font metrics are aligned for UI line spacing; the font files are unmodified.

## Project-generated prologue illustration

`assets/illustrations/prologue_return_v2.png` is original project artwork generated and edited with the built-in ImageGen tool on 14 October 2026. The first trial is retained as `prologue_return_v1.png`. The second version changes the three riders into equipped campaign veterans, following the user's feedback; the castle and overall composition are retained. This entry records provenance, not a third-party asset-pack license. Generation and editing prompts are preserved in `Art/illustration_sources/prologue-return-v1.txt` and `prologue-return-v2.txt` at the project root.

`assets/illustrations/prologue_study_v1.png` was generated with the built-in ImageGen tool on 14 October 2026, using the approved `prologue_return_v2.png` solely as a reference for technique and palette. It depicts the castle's working study with a hearth, worn furniture and estate accounts, and is used in prologue scenes 3 and 4. The complete prompt is preserved at `Art/illustration_sources/prologue-study-v1.txt` in the project root. This records project-art provenance, not a third-party asset-pack license.

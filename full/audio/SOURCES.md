# Recordings

The clips in this folder are short excerpts of recordings. They were trimmed, faded, and peak-normalized. They were not synthesized. Levels in the game still come from `mixFor` and `bedFor` in `src/audio.js`. A silent layer is gain 0. There is no noise bed.

Five street loops are in `street/`. They were trimmed, given an 80 ms loop seam, and peak-normalized. They were not synthesized. `nearestTune` and `nearestCall` still report who is closest, including a bolero or a globero who has no file. Playback skips a resting act and a role with no tape, then plays the next one that has a recording.

- `street/mariachi.ogg` is mariachi with accordion, recorded on a New York subway in 2009 by pianoplayerdavid@yahoo.com. CC0 1.0. https://archive.org/details/MariachiOnTheSubway It is not a trio in a Centro plaza.
- `street/organ.ogg` is a barrel organ playing “Cien años” in La Obrera market, Mexico City, by felix.blume. CC0. https://freesound.org/people/felix.blume/sounds/218491/ The shipped file is the public preview of that recording.
- `street/tamales.ogg` is a bicycle vendor of Oaxaca-style tamales calling under a balcony on Calle General Prim, Colonia Juárez, Mexico City, by tilllt. CC BY 4.0. https://freesound.org/people/tilllt/sounds/52382/ The shipped file is the public preview of that recording.
- `street/huehuetl.ogg` is a huehuetl at the Zócalo, July 2019, by XiscoVar. CC0. https://freesound.org/people/XiscoVar/sounds/482884/ It is the drum in the square. It is not a full conchero dance, and it has no ayoyotes and no chant. The shipped file is the public preview of that recording.
- `street/cumbia.ogg` is a cumbia band on a stopped parade float in Saravena, Colombia, 2016, by kyles. CC0. https://freesound.org/people/kyles/sounds/405031/ It is not a Mexico City sonidero. No sonidero tape under a license this project can ship was found. The shipped file is the public preview of that recording.

The bolero stays silent. No shoeshine recording and no Mexican bolero under a shippable license was found. The globero and the other vendors stay silent. Their calls are not the tamalero tape.

## Licenses

Sunset Editorial / USC sound libraries on archive.org are CC0 1.0. The item pages:

- Guns: https://archive.org/details/SSE_Library_GUNS
- Vehicles: https://archive.org/details/SSE_Library_VEHICLES
- Aircraft: https://archive.org/details/SSE_Library_AIRCRAFT
- Explosions: https://archive.org/details/SSE_Library_EXPLOSIONS
- Footsteps: https://archive.org/details/SSE_Library_FOOTSTEPS
- Fight: https://archive.org/details/SSE_Library_FIGHT
- Metal: https://archive.org/details/SSE_Library_METAL
- Fire: https://archive.org/details/SSE_Library_FIRE
- Alarms: https://archive.org/details/SSE_Library_ALARMS
- Wood: https://archive.org/details/SSE_Library_WOOD
- Tools: https://archive.org/details/SSE_Library_TOOLS
- Ambience: https://archive.org/details/SSE_Library_AMBIENCE
- Birds: https://archive.org/details/SSE_Library_BIRDS
- Water: https://archive.org/details/SSE_Library_WATER

Car engines are also CC0 1.0, with no creator field on the item: https://archive.org/details/car-engines

Rain is `Rain (1).ogg` by ezwa, public domain (PDSounds), https://commons.wikimedia.org/wiki/File:Rain_(1).ogg

Church bells are `Church bells - Leverkusen, 2007` by natalie, public domain, https://commons.wikimedia.org/wiki/File:Church_bells_-_Leverkusen,_2007.oga

`manifest.json` names the source file and the time each clip was cut from.

## What is not the machine it stands in for

These are the nearest legal recordings, and they are the wrong object. They are not relabeled.

- `street/cumbia.ogg` is a parade band in Saravena. The sonidero on the sidewalk plays it because no sonidero recording could be shipped. The file is not named sonidero.
- `street/huehuetl.ogg` is one drum at the Zócalo. The conchero dances to that drum. It is not the whole dance.
- `street/mariachi.ogg` is a subway group, not a plaza trio.
- `engines/mixer.ogg` is a Volkswagen Golf GTI VII. No cement-mixer tape was available. It sounds like a hot hatch.
- `engines/fire.ogg` is a bulldozer, continuous construction diesel. It is not a fire apparatus.
- `engines/ladder.ogg` is a construction crane lifting. It is not a ladder truck.
- `engines/swat.ogg` is a short military tank or bulldozer take. It is not a SWAT van.
- `engines/apc.ogg` is an army tank.
- `engines/ambulance.ogg` is steady driving from inside a car. The medic siren is what marks it.
- `engines/foodtruck.ogg` is a large old car pulling in and stopping. It is not a step van.
- `engines/pickup.ogg` is a car on dirt. It is not a pickup truck.
- `engines/combi.ogg` is a second van take. Birds are in the recording.
- `engines/jet.ogg` and `world/turbine.ogg` are two different stretches of a V-2 rocket motor. They are not a jet airliner. The airport bed is that rocket, played low.
- `world/siren-medic.ogg` is a French two-tone siren. It is not a faster electronic hi-lo built in the game.
- `world/siren-police.ogg` is an old mechanical police siren.
- `world/step.ogg` and `world/step-b.ogg` are footsteps on a dirt trail, not concrete.
- `weapons/baton.ogg` is a gavel. `weapons/bat.ogg` is a wooden object falling. `weapons/beanbag.ogg` is a third hit from the same western shotgun tape as the coach gun and the auto twelve.
- `weapons/machinep.ogg`, `weapons/fold9.ogg`, and `weapons/drum9.ogg` are three different bursts from one Tommy-gun tape.
- `weapons/knife.ogg` and `weapons/machete.ogg` are two chops from one blade tape.
- `weapons/flame.ogg` is a flamethrower burst, cut at 40.4 s from `FIREBrst_Flame thrower_CS_USC.mp3` in the USC fire library. It is that take, the sustained roar. It is not a synthesized jet.

Everything else is a different file per archetype, and a different hit per weapon. A patrol officer's shot with no weapon id plays `weapons/carbine556.ogg`.

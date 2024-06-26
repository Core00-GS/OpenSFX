# OpenSFX README

## Table of Contents:

- 1.0 [About](#10-about)
  - 1.1 [License](#11-license)
- 2.0 [Installing](#20-installing)
  - 2.1 [Installing manually](#21-installing-manually)
  - 2.2 [Installing using the Online Content service](#22-installing-using-the-online-content-service)
- 3.0 [Obtaining the source](#30-obtaining-the-source)
  - 3.1 [Compiling the source](#31-compiling-the-source)
  - 3.2 [Contributing](#32-contributing)
- 4.0 [Credits](#40-credits)
  - 4.1 [Sound credits of source sounds](#41-sound-credits-of-source-sounds)
  - 4.2 [Sound editors](#42-sound-editors)
  - 4.3 [Other authors](#43-other-authors)
  - 4.4 [License reference](#44-license-reference)


## 1.0 About

OpenSFX is a set of base sounds for OpenTTD and is the result of the
"Sound Effects Replacement" project.

The main goal of OpenSFX is to provide a set of free sounds which
make it possible to play OpenTTD without requiring the (copyrighted) files
from the Transport Tycoon Deluxe CD.

The OpenSFX sounds are free as in 'free beer' and free
as in 'freedom'.

### 1.1 License

OpenSFX is free software, you are allowed to freely use, copy, modify and
share this, even commercially, as long you follow the licenses.

The OpenSFX sound collection as a whole is licensed under the
    Creative Commons Attribution-ShareAlike 3.0 Unported
license.

All other files, including text files, scripts, etc. are
dual-licensed under:
    GNU General Public License version 2 (or later)
and
    Common Development and Distribution License 1.1.

You can find the full license texts in license.txt.

Note about individual sound files:

Each individual sound file in OpenSFX is additionally
released under another license, which is either the same as
the overall license or a more permissive one.
See "src/opensfx.psfo" in the source repository to see
which license it is.
So if you want to use a specific sound file from OpenSFX, you
are free to choose whether the overall sound license
mentioned above applies to you, or the license of the specific
sound file.

## 2.0 Installing

OpenSFX is available from at least three locations. This readme will
only cover the official download locations. We cannot support third
party download locations and we cannot refund your money if you have
paid money for OpenSFX.

There are three ways to get the latest stable release:
- If you are new to OpenTTD, you do not have access to the original
  Tranport Tycoon Deluxe files and you are using the Windows installer
  to install OpenTTD you can select OpenSFX to be downloaded during
  the installation of OpenTTD.

- If you are new to OpenTTD and do not have access to the original
  Tranport Tycoon Deluxe files, you will have to download and install
  OpenSFX manually. This is really not that difficult as it may
  sound, so do not worry too much about that.
  - Download location:
    https://www.openttd.org/downloads/opensfx-releases/latest.html
  - Installation instructions:
    Installing OpenSFX Manually.

- If you already have OpenTTD up and running, the in-game Online Content
  service is the easy way to obtain OpenSFX.
  - Download location:
    use the in-game Online content service
  - Installation instructions:
    Installing OpenSFX using the Online Content service.

### 2.1 Installing Manually

1. First, make sure that you have downloaded and installed at least
   OpenTTD version 1.0.0 or a recent nightly.
2. Next, download the latest OpenSFX package. (stable nightly)
3. Unpack the zip into the OpenTTD's /baseset directory. There is no
   need to unpack the tar file, so just leave it as it is. Your
   OpenTTD /baseset directory is either located in:
   - An OpenTTD folder in your user account's home directory:
     - Windows: C:\Users\<username>\Documents\OpenTTD
     - macOS: ~/Documents/OpenTTD
     - GNU/Linux: ~/.openttd
   - The OpenTTD installation directory.
4. Run OpenTTD.
5. In the main menu of the game, click the Game Options button.
   The Game Options dialog will appear.
6. Select OpenSFX from the drop-down list below Base sound set if
   that's not selected already (bottom left of window). Close the
   window using the × in the upper left corner.
   - If you did not install the original Tranport Tycoon Deluxe base
     sounds during the installation of OpenTTD, you can skip this step.
   - If you installed the original Tranport Tycoon Deluxe base sounds
     as well, this is where you can switch base sound sets.

### 2.2 Installing using the Online Content service

This method uses the Online content service (BaNaNaS) to download OpenSFX.
In order to use this, you need a working OpenTTD (at least 1.0.0).

1. Start OpenTTD and on the main menu click the Check online content
   button. A new window will pop up.
   - If OpenTTD does not start, follow the manual installation procedure.
2. Find the OpenSFX entry from the list at the left. You can use the
   search box in the upper right corner of the window.
3. Click the little square in front of the OpenSFX entry in order to
   mark it for download.
4. Click the Download button in the bottom right corner. After
   download, close the open windows.
5. In the main menu of the game, click the Game Options button. The Game
   Options dialog will appear.
6. Select OpenSFX from the drop-down list below Base sound set if
   that is not selected already (bottom left of window). Close the
   window using the × in the upper left corner.
   - This is where you can switch base sound sets.


## 3.0 Obtaining the source

The OpenSFX source is available in a Git repository.
You can use Git to do a checkout from this address:

> git clone https://github.com/OpenTTD/OpenSFX.git

For releases you can download the (released) tarballs from:

> https://www.openttd.org/downloads/opensfx-releases/latest.html

### 3.1 Compiling the source

For compiling the source you need:
- catcodec (https://www.openttd.org/downloads/catcodec-releases/latest)
- (GNU) make
- md5sum
- cut
- a sh compatible shell
- git if you want it to be properly versioned
If you want to package you also need tar, zip and possibly bzip2.

### 3.2 Contributing

Contributing to OpenSFX can be done in several ways, but they generally end
up with providing (improved) samples for the set. If you have got a better
sample than we currently have you can make that know via an issue at:

> https://github.com/OpenTTD/OpenSFX/issues

Please mention who made the original samples and that the sample has been
released under the Creative Commons Attribution-ShareAlike 3.0 Unported
license or a license that allows us to release it under that license
(for example, Creative Commons Attribution 3.0 Unported or
Creative Commons Zero 1.0).

## 4.0 Credits

Most sounds come from freesound.org and pdsounds.org and were edited
by OpenTTD contributors in order to make them suitable for the game. Most
source sounds have been released under libre licenses like CC BY 3.0,
allowing sharing and remixing.

To see detailed license info about the actual sound files in OpenSFX,
see "src/opensfx.psfo" in the source repository.

### 4.1 Sound credits of source sounds

This section gives credit to the original sound authors, i.e. the
sounds before they were edited. All sounds are sorted by their
ORIGINAL license or legal status. This does not change
the overall OpenSFX license.
The name of the author, the origin website, the original file name
and the URL (if available) are given, in this order.

#### 4.1.1 Public Domain
- "Aldor" from "pdsounds.org"
  - Ascenseur / Elevator
- David R Barnes ("earthcalling") from "pdsounds.org"
  - Corner of a sheep field in summer

#### 4.1.2 CC0 1.0

- "1sticky8" from "freesound.org"
  - Dumpster_Diving.wav
    https://freesound.org/people/1sticky8/sounds/78484/
- "Bidone" from "freesound.org"
  - Affen schreit.mp3
    https://freesound.org/people/Bidone/sounds/67361/
- Elaine Miller ("Miselaineous" at "freesound.org")
  - elaine-growl.wav
    https://freesound.org/people/Miselaineous/sounds/63668/
- "Matias.Reccius" from "freesound.org"
  - crashB.wav
    https://freesound.org/people/Matias.Reccius/sounds/45102/
- "Necrosensual" from "freesound.org"
  - aluminum02.wav
    https://freesound.org/people/Necrosensual/sounds/33906/
- "Q.K." from "freesound.org"
  - Metal_03.wav
    https://freesound.org/people/Q.K./sounds/56253/
- "sagetyrtle" from "freesound.org"
  - crash.wav
    https://freesound.org/people/sagetyrtle/sounds/40158/
- "saphix" from "freesound.org"
  - file0375.mp3
    https://freesound.org/people/saphix/sounds/36794/
- "simon.rue" from "freesound.org"
  - Boink_v3.wav
    https://freesound.org/people/simon.rue/sounds/61847/
- "SlykMrByches" from "freesound.org"
  - splattt.mp3
    https://freesound.org/people/SlykMrByches/sounds/55234/
- Tom Haigh ("audible-edge" at "freesound.org")
  - Nissan Maxima burnout (04-25-2009).wav
    https://freesound.org/people/audible-edge/sounds/71740/
- "Metzik" from "freesound.org"
  - Train passby (tape stop).wav
    https://freesound.org/people/Metzik/sounds/387878/
- "SpaceJoe" from "freesound.org"
  - Bird Noise - 1.wav
    https://freesound.org/people/SpaceJoe/sounds/507257/
  - Bird Noise - 12.wav
    https://freesound.org/people/SpaceJoe/sounds/507254/
- "MrVasLuk" from "freesound.org"
  - Airplane propeller.wav
    https://freesound.org/people/MrVasLuk/sounds/333203/
- "ibisradio" from "freesound.org"
  - 5_Navy-Blue-Angels-jets_CLIP.wav
    https://freesound.org/people/ibisradio/sounds/328446/
- "mcpable" from "freesound.org"
  - Industrial Air Horn.wav
    https://freesound.org/people/mcpable/sounds/131930/
- "ecfike" from "freesound.org"
  - A Tree Falling Down.wav
    https://freesound.org/people/ecfike/sounds/139952/
- "fkurz" from "freesound.org"
  - cutting_tree.wav
    https://freesound.org/people/fkurz/sounds/169127/
- "JarredGibb" from "freesound.org"
  - Cow - Moan 2 - 96kHz.wav
    https://freesound.org/people/JarredGibb/sounds/233146/
- "marvman" from "freesound.org"
  - shaker2.wav
    https://freesound.org/people/marvman/sounds/51317/
- Jan Schupke alias "Vehicle" from "opengameart.org"
  - vial-glass-square-cinnamon-sticks-open-02.wav
    https://opengameart.org/content/fantasy-accessory-sfx-library
- "Mark_Ian" from "freesound.org"
  - RRCrossing.wav
    https://freesound.org/people/Mark_Ian/sounds/240639/
- "Beviceps" from "freesound.org"
  - Cartoon - Slurp!.wav
    https://freesound.org/people/Breviceps/sounds/445974/
- "ristooooo1" from "freesound.org"
  - Bubbles 001.wav
    https://freesound.org/people/ristooooo1/sounds/539823/
- "musicmasta1" from "freesound.org"
  - CarStartSkidCrash.wav
    https://freesound.org/people/musicmasta1/sounds/131385/

#### 4.1.2 CC BY 3.0

- "AGFX" from "freesound.org"
  - Squeeky ball Toy_1.L.wav
    https://freesound.org/people/AGFX/sounds/42940/
- "Anton" from "freesound.org"
  - wind1.wav
    https://freesound.org/people/Anton/sounds/2690/
- "Benboncan" from "freesound.org"
  - Circular saw crosscutting.wav
    https://freesound.org/people/Benboncan/sounds/60178/
- "cfork" from "freesound.org"
  - boing_raw.aif
    https://freesound.org/people/cfork/sounds/7967/
- Derek Murphy ("robbiesurp" at "freesound.org")
  - wfl5.5_snap.wav
    https://freesound.org/people/robbiesurp/sounds/3154/
- "www.digifishmusic.com" ("digifishmusic" at "freesound.org")
  - Passenger jet departs 2.wav
    https://freesound.org/people/digifishmusic/sounds/54965/
- "dobroide" from "freesound.org"
  - 20060419.horse.neigh.wav
    https://freesound.org/people/dobroide/sounds/18229/
- "Goldy-sama" from "freesound.org"
  - bulle.wav
    https://freesound.org/people/Goldy-sama/sounds/4239/
- "Halleck" from "freesound.org"
  - JacobsLadderLong2.flac
    https://freesound.org/people/Halleck/sounds/19483/
- "han1" from "freesound.org"
  - Car start and drive.mp3
    https://freesound.org/people/han1/sounds/19025/
  - claxon.wav
    https://freesound.org/people/han1/sounds/19026/
- "man" from "freesound.org"
  - swosh.aif
    https://freesound.org/people/man/sounds/14609/
- "Marec" from "freesound.org"
  - metro.wav
    https://freesound.org/people/Marec/sounds/17601/
- "icmusic" from "freesound.org"
  - london bus approaches & leaves.wav
    https://freesound.org/people/icmusic/sounds/36897/
- "jascha" from "freesound.org"
  - kick_1.wav
    https://freesound.org/people/jascha/sounds/2837/
- "JFBSAUVE" from "freesound.org"
  - CHAINSAW.wav
    https://freesound.org/people/JFBSAUVE/sounds/19898/
- "joedeshon" from "freesound.org"
  - slide_whistle_down_fast_01.wav
    https://freesound.org/people/joedeshon/sounds/79672/
- "l0calh05t" from "freesound.org"
  - in the smithy 2.wav
    https://freesound.org/people/l0calh05t/sounds/19027/
- "Leady" from "freesound.org"
  - Dropping a large gun.wav
    https://freesound.org/people/Leady/sounds/12735/
- Leon Milo ("milo" at "freesound.org")
  - msfinmarken_Bergen.aif
    https://freesound.org/people/milo/sounds/23452/
  - ship2_bergen.aif
    https://freesound.org/people/milo/sounds/23722/
- "lonemonk" from "freesound.org"
  - Approx 850 - Enthusiast Audience.wav
    https://freesound.org/people/lonemonk/sounds/31169/
- "NoiseCollector" from "freesound.org"
  - CRASH2.wav
    https://freesound.org/people/NoiseCollector/sounds/2792/
- "patchen" from "freesound.org"
  - Locomotive 1 Distant horn.wav
    https://freesound.org/people/patchen/sounds/17851/
- "Pooleside" from "freesound.org"
  - nnb04_maxed.wav
    https://freesound.org/people/Pooleside/sounds/21558/
- Richard Frohlich ("FreqMan" at "freesound.org")
  - whoosh06.wav
    https://freesound.org/people/FreqMan/sounds/25074/
- "roscoetoon" from "freesound.org"
  - t_start1.mp3
    https://freesound.org/people/roscoetoon/sounds/26814/
- "Sedi" from "freesound.org"
  - ae_51_m.wav
    https://freesound.org/people/Sedi/sounds/70899/
- "Stickinthemud" from "freesound.org"
  - Bike Horn double toot.wav
    https://freesound.org/people/Stickinthemud/sounds/27882/
- "suonho" from "freesound.org"
  - ELEMENTS_WATER_02_Phasin-bubbles.wav
    https://freesound.org/people/suonho/sounds/17783/
- "VEXST" from "freesound.org"
  - Snare 4.wav
    https://freesound.org/people/VEXST/sounds/26903/
- "bigpickle51" from "freesound.org"
  - Landing Jet 5 (Close).wav
    https://freesound.org/people/bigpickle51/sounds/219469/
- "Cheeseheadburger" from "freesound.org"
  - Plane Cessna start stop.wav
    https://freesound.org/people/Cheeseheadburger/sounds/141519/
- "eliasheuninck" from "freesound.org"
  - steam train horn 01.wav
    https://freesound.org/people/eliasheuninck/sounds/170464/
- "Bluesy1905" from "freesound.org"
  - air hammer half close.wav
    https://freesound.org/people/Bluesy1905/sounds/344934/
- "InspectorJ" from "freesound.org"
  - Slide Whistle, Descending, B (H1).wav
    https://freesound.org/people/InspectorJ/sounds/410804/
- "swordofkings128" from "freesound.org"
  - "raw_bubblingdrink.ogg"
    https://freesound.org/people/swordofkings128/sounds/398029/

#### 4.1.3 CC BY-SA 3.0

- Lorenzo Sutton ("lorenzosu" at "freesound.org"):
  - helicopterRaw_16sec.wav
    https://archive.org/details/helicopterRaw_16sec

### 4.2 Sound editors

Editing/(re)mixing was done by:
- Janis Lukss ("Pendrokar" at "wiki.openttd.org")
- "janusz" from "dev.openttdcoop.org"
- "Jklamo" from "wiki.openttd.org"
- Remko Bijker ("Rubidium" at "dev.openttdcoop.org")
- Richard Wheeler ("Zephyris" at "dev.openttdcoop.org")
- "Wuzzy" from "tt-forums.net"

A detailed list of who has worked on what sample is available in the
file "src/opensfx.psfo" in the source repository.

### 4.3 Other authors

This is a list of sound creators that contributed
their work directly to OpenSFX:
- Remko Bijker ("Rubidium" at "dev.openttdcoop.org")
  - Started the OpenSFX project, author of the initial scripts,
    text files, chose most of the initial sounds
- Janis Lukss ("Pendrokar" at "wiki.openttd.org")
  - Own recordings/mixes
- Timo A. Hummel ("Felicitus" at "dev.openttdcoop.org")
  - Own work

### 4.4 License reference

You can find the complete license texts here:

- CC0 1.0: <https://creativecommons.org/publicdomain/zero/1.0/>
- CC BY 3.0: <https://creativecommons.org/licenses/by/3.0/>
- CC BY-SA 3.0: <https://creativecommons.org/licenses/by-sa/3.0/>
- GNU GPLv2: <https://www.gnu.org/licenses/old-licenses/gpl-2.0.html>
- CDDL 1.1: <https://spdx.org/licenses/CDDL-1.1.html>

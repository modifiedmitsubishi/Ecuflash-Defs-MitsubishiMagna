# Ecuflash Mitsubishi Magna Definitions

This repository has been salvaged from the now defunct **ModifiedMitsubishi** forums and is largely the work of `Andrew I MacIntyre` (WytWun).

While apparently not as extensive in map support as others, I have managed to cross check the maps included with several different reference sources and am reasonably confident they're correct. The maps included cover most of the tuning done by the likes of SKR, from what I've seen of 2 different SKR modified ROMs, except for some of the periphery bits (as they're called in the Evo community; essentially option flags or switches) which I'm still attempting to decode/validate.

TJ/KJ onwards auto ECUs have 512kB ROMs. ECUFlash by default doesn't contain a vehicle type that will read/flash the whole ROMs, though using the Evo 9 vehicle type (in either ECUFlash or Evoscan) may work for some TL/TW auto ECUs. To read/reflash the full 512kB with ECUFlash, install the attached custom "read template" file in the "read templates" subdirectory in the rommetadata directory of the ECUFlash installation, and then select the "Evo7 GT-A/01+ Magna AT" vehicle type. The auto ECU definitions in the above attachment expect 512kB ROM files - please read the enclosed README.txt to see how to use 256kb incomplete ROM files with them. ECUFlash will trash files if you get it wrong.

vehicle support:
* Mitsubishi Magna TH-TW AUDM
* Mitsubishi Verada KH-KW AUDM
* Mitsubishi Diamante Second Generation USDM

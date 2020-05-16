# ChillyTurtleTF2CustomConfig
ChillyTurtle's TF2 configs.

## Warning
Some of the options may not be your fit. Please look over the configs before you decide to use these commands. Look out for the Net Settings in autoexec.cfg.

## Installation
- Put `autoexec.cfg`, `Bind.cfg`, `MaxFrames.cfg`, `TransparentViewmodels.cfg`, `listenserver.cfg` in the tf/cfg folder.
- Take out the class configs from the class configs folder and put it in the tf/cfg folder as well.
- Choose one between `nohitscanviewmodels.vpk` and `noprimarysecondaryviewmodels.vpk` to put in the tf/custom folder, or just don't.
## Contents and Main Features

#### autoexec.cfg
- `fps_max 60`
- `sv_cheats 1`
- `sv_allow_point_servercommand always`
- `cl_interp 0.0303`
- Recommended launch options (you have to set these up yourself)
- Executes `Binds.cfg`, `MaxFrames.cfg`, and `TransparentViewmodel.cfg` (disabled, uncomment to use)
- Better network settings
- Disable mouse acceleration
- Optimized advanced multiplayer options for gameplay
- Voice chat toggle
- Null movement script
- Woolen's scoreboard net_graph config

#### class configs
- exec binds.cfg on all classes
- `cl_interp 0.0304` on hitscan classes (disabled, all class have `cl_interp 0.0303` now)
- `cl_interp 0.0152` on projectile classes (disabled, all class have `cl_interp 0.0303` now)
- Extra disguise binds for spy
  - Enemy medic holding medigun disguise
  - Undisguise
  - Enemy scout disguise
  - Friendly scout disguise

#### Binds.cfg
- Personal binds shared among all classes (minor exception for spy)

#### MaxFrames.cfg
- `mat_phong 0`
- `mat_bumpmap 1`
- `mat_specular 1`
- `host_thread_mode 0`
- Pyrovision disabled
- Facial features disabled
- Eyes disabled
- Ragdolls disabled
- Gibs disabled
- Sprays disabled
- Shadows disabled
- High model detail
- High texture detail
- See-through water
- Jigglebones enabled

#### TransparentViewmodels.cfg
- Commands for the use of transparent viewmodels

#### listenserver.cfg
- `sv_cheats 1`
- `sv_allow_point_servercommand always`
- `net_fakelag 20` (disabled, uncomment to use)

## Credits
- aWoolenSleevelet
  - Basis for autoexec.cfg, old_maxframes.cfg, scoreborad net_graph config
- Comanglia, Chris, Mastercoms
  - Performance config in maxframes.cfg
  - Net settings in autoexec.cfg
- Aar
  - Voice chat toggle in autoexec.cfg

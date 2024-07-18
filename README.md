# BodhiraLightingController
This is a touchdesigner-based software to live-control the kinetic light installation "Bodhira". The Project provides a UserInterface and allows to controll lighting effects and color as well as movement states in a live setup e.g. live-music, audiovisual performances, etc.

## Contents

- [Overiview & UI](#Structure)
- [Efect- and Color Presets](#effektübersicht)
- [Controls](#controls)
- [DMX-Overview](#dmx-overwie)
- [Beitragende](#beitragende)
- [Lizenz](#lizenz)



| 1    | Tap-Tempo              | Unnamed: 2                 | Unnamed: 3                                                                                                          |
|:-----|:-----------------------|:---------------------------|:--------------------------------------------------------------------------------------------------------------------|
|      | 0                      | off                        |                                                                                                                     |
|      | 255                    | on                         | for taping in the Tempo, controls effect and Motor Speed                                                            |
| 2.0  | Main-Dimmer            |                            |                                                                                                                     |
|      | 0 - 255                | Dimmer-Value               | set the global brightness                                                                                           |
| 3.0  | Color-Presets          |                            |                                                                                                                     |
|      |                        | Color-Preset 1             | dark blue - red                                                                                                     |
|      |                        | Color-Preset 2             |                                                                                                                     |
|      |                        | Color-Preset 3             |                                                                                                                     |
|      |                        | Color-Preset 4             |                                                                                                                     |
| 4.0  | Gobos                  |                            |                                                                                                                     |
|      |                        | Gobo 1                     | Circle                                                                                                              |
|      |                        | Gobo 2                     | Line                                                                                                                |
|      |                        | Gobo 3                     | Star                                                                                                                |
| 5.0  | Movement               |                            |                                                                                                                     |
|      | 0 - 255                | Movement Speed             | control the speed of the movement                                                                                   |
| 6.0  | Pattern                |                            |                                                                                                                     |
|      | 0 - 255                | Pattern Intensity          | control the intensity of a built-in pattern                                                                         |
| 7.0  | Strobe                 |                            |                                                                                                                     |
|      | 0                      | off                        |                                                                                                                     |
|      | 255                    | on                         | activate strobe effect                                                                                              |
| 8.0  | Color-Temperature      |                            |                                                                                                                     |
|      | 0 - 255                | Temperature Value          | control the color temperature                                                                                       |
| 9.0  | Motor-Speed            |                            |                                                                                                                     |
|      | 0 - 255                | Motor Speed Value          | control the speed of the motor                                                                                      |
| 10.0 | Sound-Mode             |                            |                                                                                                                     |
|      | 0                      | off                        |                                                                                                                     |
|      | 255                    | on                         | activate sound mode                                                                                                 |
| 11.0 | Freeze-Frame           |                            |                                                                                                                     |
|      | 0                      | off                        |                                                                                                                     |
|      | 255                    | on                         | freeze the current frame                                                                                           |
| 12.0 | Blackout               |                            |                                                                                                                     |
|      | 0                      | off                        |                                                                                                                     |
|      | 255                    | on                         | activate blackout mode                                                                                              |
| 13.0 | Slow-Down              |                            |                                                                                                                     |
|      | 0                      | off                        |                                                                                                                     |
|      | 255                    | Slow-Down                  | temporarily slow down the movement, good for syncing movement to beat                                               |
| 14.0 | Beat-Enhancer          |                            |                                                                                                                     |
|      | 0 - 255                | Beat-Enhancer Intensity    | control the intensity of an automatic, beat-matched simple dim effect                                               |
| 15.0 | Auto-Color Shift       |                            |                                                                                                                     |
|      | 0 - 255                | Auto Color Shift Intensity | control the intensity of a subtle, continuous automatic color shift                                                 |
| 16.0 | Feedback               |                            |                                                                                                                     |
|      | 0 - 255                | Feedback Intensity         | control the intensity of a simple feedback effect, good for smoothing out transitions or performative playfulness   |
| 17.0 | AutoPilot              |                            |                                                                                                                     |
|      | 0                      | off                        |                                                                                                                     |
|      | 255                    | on                         | activate audioreactive AutoPilot. Only works if audio is injected to the system. User can still control everything. |

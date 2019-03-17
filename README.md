# Run mode
Configure `run_mode` in `mbed_app.json`, this will generate a macro `MBED_CONF_APP_RUN_MODE`

Run_mode  | MIDI-IN_serial  |  Debug_serial  |  Test_functions |      Jumper
----------|-----------------|----------------|-----------------|----------------------
0: Normal |       V         |       X        |        X        |       Short
1: Debug  |       X         |       V        |        X        |       Open
2: Test   |       X         |       V        |        V        |       Open

Jumper: MIDI-IN_path

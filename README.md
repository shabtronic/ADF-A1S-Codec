# ADF-A1S-Codec
A1S-Board  and AC101 Driver files for ADF

First pass on AC101 Driver and Board Files for ADF Version:

https://github.com/espressif/esp-adf/tree/3305749c93763b7a83d030e7f30b28f3aeb1d186

Tested with examples/get-started play_mp3, play_mp3_control and play_dac

derived from

https://github.com/phkehl/esp32-a1s-audio_hal

and

https://github.com/donny681/esp-adf
Latest commit
26505bd

Installing:

You simple copy all the files over your current ADF Audio_Board and Audio_Hal directories and
idf.py menuconfig should allow you to select the A1S board.


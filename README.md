# water_table
Info on how to write the JSON (the document that interfaces between the daisy and pd): https://forum.electro-smith.com/t/quick-guide-on-setting-up-a-custom-json-file-for-pd2dsy-oopsy/4021
More JSON info: https://github.com/electro-smith/json2daisy (contains info for specific components)

hvcc compiler information: https://wasted-audio.github.io/hvcc/
Especially important here is that not all pd objects are supported by heavy. 
There are some specific heavy compatible abstractions availible here: https://github.com/Wasted-Audio/heavylib

Use plugdata for compiling: https://plugdata.org/documentation.html
For the daisy specifically stick it in bootloader mode before you compile onto it: Hold the reset button, click boot once and then let go of reset. 

# HolyC

This repository is made ideally for learning about HolyC and how it works underneath the hood of Temple OS. HolyC provides low level C functionality and speed, while also providing agility in respect to being JIT compiled. The JIT compilation feature of this language allows it to be utilized as a shell language as well within Temple OS. In some future, it would be interesting to see if the custom opcodes of Temple OS could be translated to another machine instruction (or multiple) in order to port the HolyC language (and its features) into other operating systems.

## Extracting HolyC from Temple OS

Extracting .HC.Z files from Temple OS is quite the undertaking as there is limited documentation and know how online. However following the instructions.txt within the temple_extraction directory and modifying the provided script will be able to extract the files via an ISO image.
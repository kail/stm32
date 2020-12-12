# STM32 Projects
STM32 examples, snippets, and templates

## Requirements
1. [GNU Arm Embedded Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads)
1. [OpenOCD](http://openocd.org/)
1. (Optional)[ST-Util](https://www.st.com/en/development-tools/stsw-link004.html) -- or `brew install stlink`


## Getting Started
Note: at the time of this writing I work exclusively on an OSX box, and none of this has been verified to work on other platforms.

1. Get the submodules `git submodule init; git submodule update --recursive`

## Miscellaneous

### SVD Files
These can be useful for tools that support them ([like CLion](https://blog.jetbrains.com/clion/2019/07/clion-2019-2-eap-peripheral-view-for-arm-devices/))
* https://www.st.com/resource/en/svd/stm32l4_svd.zip
* https://www.st.com/resource/en/svd/stm32f4_svd.zip

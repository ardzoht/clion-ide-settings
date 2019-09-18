# Magma EPC development settings for CLion

NOTE: To get CLion setting up the project properly, you should have the magma VM built using `make` and have it running using `make run`.

This settings repository contains preferences to setup a remote connection to magma VM, so all the CMake building, tags, libraries compilation are done remotely rather than on the host.

![clion2](https://github.com/ardzoht/clion-magma-settings/blob/master/images/clion-magma2.png)

## How to

To use it, simply go to `File -> Settings Repository`, copy the Github clone URL, and select `Overwrite Local`. This will pull those settings into your CLion preferences and setup everything for you.

![clion1](https://github.com/ardzoht/clion-magma-settings/blob/master/images/clion-magma1.png)

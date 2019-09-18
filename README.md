# Magma EPC development settings for CLion

NOTE: To get CLion setting up the project properly, you should have the magma VM built using `make` and have it running using `make run`.

This settings repository contains preferences to setup a remote connection to magma VM, so all the CMake building, tags and even the project run is done remotely rather than on the host.

## How to

To use it, simply go to `File -> Settings Repository`, copy the Github clone URL, and select `Overwrite Local`. This will pull those settings into your CLion preferences and setup everything for you.


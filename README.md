# flm_for_openocd

This repository currently contains the compiled binary of the CMSIS flash loaders (FLM) from several MCU vendors.

The FLMs are to be used with the OpenOCD generic cmsis flash driver, which was first developed by the Cypress fork.

By using the generic cmsis flash driver, it is easier to add flash programming support for the new device without having to compile the OpenOCD.

After cloning or download the repo, copy the flm folder and place it along side the OpenOCD "scripts" folder.

The example target configurations assume the "flm" to be in the same level as the "scripts" folder.

The future plan is to replace the binary FLMs with source codes, and compiled by the user with GCC.

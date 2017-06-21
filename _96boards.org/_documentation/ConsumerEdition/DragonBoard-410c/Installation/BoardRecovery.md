---
layout: empty-container-page
page_title: DragonBoard-410c Installation - Board Recovery
permalink: /documentation/ConsumerEdition/DragonBoard-410c/Installation/BoardRecovery.md/
breadcrumb-page_title: DragonBoard-410c Board Recovery
breadcrumb-section: Documentation
breadcrumb-section-two: Consumer Edition
breadcrumb-section-three: DragonBoard-410c
breadcrumb-section-four: Installation
breadcrumb-subpage_title: Board Recovery
description: |-
    This page outlines steps needed to recover your DragonBoard-410c development board from a bricked software state.
    This instruction set is suggested to those who are experiences boot issues due to corruption in the file system and/or other software components.
---
# DragonBoard 410c Board Recovery

This page outlines steps needed to recover your DragonBoard 410c board from a bricked software state. This instruction set is suggested to those who are experiences boot issues due to a corrution in the file system and/or other software components.

There are a couple ways to recover your DragonBoard 410c from a "bricked" state.

## SD card Recovery image

In most cases this will be your sure-fire way to recover your board from a software bricked state. A recovery image has been created and made ready to be flashed onto a micro SD card. Simply download the SD card recovery image, and follow the sd card installation instructions found on our [Installation page](README.md).

- Download [SD Card Recovery image](http://builds.96boards.org/releases/DragonBoard-410c/linaro/rescue/latest/DragonBoard-410c_sdcard_rescue-*.zip)
- Choose host machine under SD card installation instructions from [Installation Page](README.md)

> Note: For those already familiar with the SD card flashing process, 96Boards build folder can be found [here](http://builds.96boards.org/releases/DragonBoard-410c/linaro/rescue/latest/)

## Fastboot recovery

In many cases, simply re-flashing the bootloader, boot image, and root file system, using the [fastboot method](README.md#fastboot-method) is enough. While the generic fastboot method might not always work due to certain complications, the sd card recovery image is always available (as seen above).
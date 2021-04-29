# Change Log
The version update instructions record each important update point for everyone to track and understand.

## Release Notes
- Date: Version update date.
- Firmware: Targeted OpenWrt firmware.
- Types: ADD / UPDATE / TOOL / BUG
- Importance: The difference between five stars (✩✩✩✩✩), the more stars the more important.
- Path: Link to related files.
- description: Detailed description of the update.


| Date | Firmware | Types | Importance | Path | description |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 2021.04.27 | All | ADD | ✩✩✩ | [Actions](https://github.com/ophub/op/blob/main/.github/workflows/build-openwrt-s9xxx.yml) | Add use Actions packaging instructions. |
| 2021.04.17 | All | ADD | ✩✩✩ | [5.10.31.TF](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.10.31.TF) | Support directly using the 3 kernel files provided by Flippy for OpenWrt packaging. |
| - | All | ADD | ✩✩✩ | [5.4.113](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.113) | Support directly using the 3 kernel files provided by Flippy for OpenWrt packaging. |
| 2021.04.10 | All | ADD | ✩✩✩ | [kernel](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel) | Replace all kernels with Flippy's standard kernel. |
| 2021.04.09 | All | ADD | ✩✩✩✩✩ | [openwrt-kernel](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/amlogic-kernel/build_kernel/openwrt-kernel) | Extend the script function, on the basis of kernel replace, Added the function of making Flippy's standard kernel 3 files. |
| 2021.04.07 | All | ADD | ✩✩✩✩✩ | [openwrt-kernel](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/amlogic-kernel/build_kernel/openwrt-kernel) | Add kernel replace function, support the use of `Flippy` kernel or the reorganized kernel of this repository for `openwrt` kernel upgrade (different from `openwrt-update`, this operation only replaces the kernel). |
| - | All | ADD | ✩✩✩ | [5.4.108](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.108) | Support directly using the 3 kernel files provided by Flippy for OpenWrt packaging. |
| 2021.03.28 | All | ADD | ✩✩✩ | [5.4.108](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.108) | Add New kernel. |
| - | All | ADD | ✩✩✩ | [5.10.26.TF](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.10.26.TF) | Add New kernel. |
| 2021.03.27 | All | ADD | ✩✩✩ | [openwrt-master](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/router-config/openwrt-master) | Add openwrt-master branch. |
| 2021.03.25 | All | UPDATE | ✩✩ | [openssl](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/common-files/patches/openssl) | Use Flippy's openssl files to increase related functions. |
| 2021.03.24 | All | UPDATE | ✩✩ | [cpustat](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/common-files/patches/cpustat) | Use Flippy's cpustat files to increase related functions. |
| 2021.03.23 | All | UPDATE | ✩✩ | [openwrt-version](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/common-files/files/usr/bin/openwrt-version) | Add openwrt version information view command: `openwrt-version`. |
| 2021.03.21 | All | UPDATE | ✩✩✩✩✩ | [openwrt-backup](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/common-files/files/usr/bin/openwrt-backup) | Added `flippy's` retention configuration upgrade strategy in the `openwrt-update` function. |
| 2021.03.12 | All | UPDATE | ✩✩✩✩✩ | [make](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/make) | Optimize the directory structure to increase the readability of the program. |
| - | All | UPDATE | ✩✩✩ | [install-program](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/install-program) | Optimize the `install/update` script. |
| - | All | ADD | ✩✩✩ | [5.4.105](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.105) | Add New kernel. |
| - | All | ADD | ✩✩✩ | [5.10.23.TF](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.10.23.TF) | Add New kernel. |
| 2021.03.05 | All | ADD | ✩✩✩ | [5.4.101](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.101) | Add New kernel. |
| - | All | ADD | ✩✩✩ | [5.10.19.TF](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.10.19.TF) | Add New kernel. |
| - | All | UPDATE | ✩✩✩ | [install-program](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/install-program) | According to the latest kernel, adjusted the `install/update` script. |
| - | All | UPDATE | ✩✩✩ | [make](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/make) | According to the latest kernel, adjusted the `make` script. |
| 2021.02.28 | All | ADD | ✩✩✩✩✩ | [README.md](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/router-config/README.md) | Add detailed description of openwrt personalized compilation. |
| 2021.02.19 | All | UPDATE | ✩✩✩✩✩ | [openwrt-update](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-update) | Optimize online update method. |
| 2021.02.17 | All | ADD | ✩✩✩ | [5.4.98](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.98) | Add New kernel. |
| - | All | ADD | ✩✩✩ | [5.10.16.TF](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.10.16.TF) | Add New kernel. |
| 2021.02.15 | All | UPDATE | ✩✩✩✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | Merging scripts, common for phicomm-n1 and s9xxx-Boxes. |
| - | All | UPDATE | ✩✩✩✩✩ | [openwrt-update](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-update) | Merging scripts, common for phicomm-n1 and s9xxx-Boxes. |
| 2021.02.01 | All | UPDATE | ✩✩✩✩✩ | [make](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/make) | Add support for 5.10 kernel. |
| - | All | UPDATE | ✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | Add support for 5.10 kernel. |
| - | All | ADD | ✩✩ | [5.10.11.TF](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.10.11.TF) | Add New kernel. |
| - | All | ADD | ✩✩ | [5.4.93](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.93) | Add New kernel. |
| 2020.12.31 | All | ADD | ✩✩✩ | [5.9.16](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.9.16) | Add New kernel. |
| - | All | ADD | ✩✩✩ | [5.4.86](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.86) | Add New kernel. |
| 2020.12.13 | All | ADD | ✩✩✩✩✩ | [packaging.yml](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/.github/workflows/use-releases-file-to-packaging.yml) | Added the `Use github.com Releases rootfs file to packaging`. |
| 2020.12.12 | S9xxx | UPDATE | ✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | Added the shared partition formatting type selection, which can be changed in `$TARGET_SHARED_FSTYPE`. |
| - | N1 | UPDATE | ✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | Added the shared partition formatting type selection, which can be changed in `$TARGET_SHARED_FSTYPE`. |
| - | All | ADD | ✩✩ | [5.9.14](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.9.14) | Add New kernel. |
| - | All | ADD | ✩✩ | [5.4.83](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.83) | Add New kernel. |
| - | All | ADD | ✩✩ | [make](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/make) | Support Belink GT-King, Belink GT-King Pro and UGOOS AM6 Plus. |
| - | All | ADD | ✩✩✩✩ | [amlogic-dtb](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-dtb) | Added dtb files for Belink GT-King Pro and other boxes. |
| - | All | ADD | ✩✩✩ | [kernel](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel) | The kernel files in the repository are all updated to the latest for dtb files. |
| - | S9xxx | UPDATE | ✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | s905x3-install.sh Renamed openwrt-install |
| - | S9xxx | UPDATE | ✩✩ | [openwrt-update](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-update) | s905x3-update.sh Renamed openwrt-update |
| 2020.12.07 | S9xxx | UPDATE | ✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | update the installation script to `flippy` version. |
| - | N1 | UPDATE | ✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | update the installation script to `flippy` version. |
| 2020.11.28 | All | UPDATE | ✩ | [make](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/make) | Add firmware version information to the terminal page. |
| 2020.11.14 | All | ADD | ✩✩✩ | [5.9.8](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.9.8) | Add New kernel. |
| - | All | ADD | ✩✩✩ | [5.7.7](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.7.7) | Add New kernel. |
| 2020.11.13 | N1 | UPDATE | ✩✩✩ | [openwrt-update](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-update) | updated the Phicomm-N1 update script, which supports booting from the USB hard disk to update. |
| 2020.11.12 | All | UPDATE | ✩✩✩✩✩ | [make](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/make) | When the openwrt firmware is packaged, the auto-complete installation/update file and BootLoader file are added. |
| 2020.11.09 | All | ADD | ✩✩✩ | [make](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/make) | Add the -b parameter to support compiling multiple firmwares at the same time. For example, `./make -d -b n1_x96`. The -k parameter is expanded to support the simultaneous compilation of multiple kernels, such as `./make -d -k 5.4.60_5.9.5`. |
| 2020.11.08 | All | TOOL | ✩✩✩ | [amlogic-dtb](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-dtb) | The dtb library is added to facilitate the lack of corresponding boot files when compiling the firmware of related models with the old version of the kernel file. |
| - | All | TOOL | ✩✩✩ | update_dtb.sh | [Replaced](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/amlogic-kernel/build_kernel/openwrt-kernel) . Update kernel files in the kernel directory with the latest dtb file. |
| - | All | UPDATE | ✩✩✩✩✩ | [kernel](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel) | Supplement the old version of the kernel with the latest dtb file. |
| - | All | UPDATE | ✩✩✩ | make_use_img.sh | [Replaced](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/amlogic-kernel/build_kernel/openwrt-kernel) . When the kernel is extracted, if the file lacks a key .dtb file, the supplement will be extracted from the dtb library. |
| - | All | UPDATE | ✩✩✩ | make_use_kernel.sh | [Replaced](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/amlogic-kernel/build_kernel/openwrt-kernel) . When the kernel is extracted, if the file lacks a key .dtb file, the supplement will be extracted from the dtb library. |
| - | S9xxx | UPDATE | ✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | Added that if the dtb file is missing during installation, the download path will be prompted. |
| 2020.11.07 | All | ADD | ✩✩ | [5.4.75](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.4.75) | Add New kernel. |
| - | All | ADD | ✩✩ | [5.9.5](https://github.com/ophub/amlogic-s9xxx-openwrt/tree/main/amlogic-s9xxx/amlogic-kernel/kernel/5.9.5) | Add New kernel. |
| - | All | UPDATE | ✩✩ | make_use_img.sh | [Replaced](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/amlogic-kernel/build_kernel/openwrt-kernel) . Add fuzzy matching function. When the version specified by the script is not found, other firmware will be searched from the flippy directory. Thus, you can directly put the kernel file you want to use into the flippy directory for extraction, without manually changing the relevant parameters each time. |
| - | All | UPDATE | ✩✩ | make_use_kernel.sh | [Replaced](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/amlogic-kernel/build_kernel/openwrt-kernel) . Add fuzzy matching function. When the version specified by the script is not found, other firmware will be searched from the flippy directory. Thus, you can directly put the kernel file you want to use into the flippy directory for extraction, without manually changing the relevant parameters each time. |
| 2020.11.01 | S9xxx | ADD | ✩✩✩✩✩ | [openwrt-install](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-install) | Added the function of writing emmc partition to s9xxx series boxes. |
| - | S9xxx | ADD | ✩✩✩✩✩ | [openwrt-update](https://github.com/ophub/amlogic-s9xxx-openwrt/blob/main/amlogic-s9xxx/install-program/files/openwrt-update) | Added the function of updating emmc partition firmware to s9xxx series boxes. |
| 2020.10.25 | All | ADD | ✩ | [amlogic-s9xxx-openwrt](https://github.com/ophub/amlogic-s9xxx-openwrt) | Open this Github repository. |


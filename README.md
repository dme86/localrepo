# Gentoo Overlay

<img src="https://www.gentoo.org/assets/img/logo/gentoo-signet.png" alt="Gentoo Logo" width="150"/>

Over the years, I have used a variety of Linux distributions. While [Arch Linux](https://archlinux.org/) is my go-to choice for [x86_64](https://en.wikipedia.org/wiki/X86-64) systems, Gentoo stands out as the optimal OS for running on [ARM](https://en.wikipedia.org/wiki/ARM_architecture_family)-based hardware, such as the latest MacBook chips, particularly in virtualized environments.

Although most Gentoo packages support ARM64, some are either not available or lack full compatibility. To maintain a lightweight installation, I avoid using the [GURU overlay](https://wiki.gentoo.org/wiki/Project:GURU), opting instead to maintain this personal overlay for essential ebuilds - especially for Gentoo installations running inside virtual ARM64 machines.

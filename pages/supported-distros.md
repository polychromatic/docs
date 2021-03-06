---
layout: docs
title: Distros and Desktop Environments
permalink: /distros/
class: docs
---

## Official Packages

This software is natively provided on these distributions.

{:.has-icons}
| Distro                                            | Maintainer    |
|---------------------------------------------------|---------------|
![](/images/distros/ubuntu.svg) [Ubuntu]`*`         | [lah7]
![](/images/distros/debian.svg) [Debian]            | [lah7]
![](/images/distros/arch.svg) [Arch / Manjaro]      | [z3ntu]
![](/images/distros/fedora.svg) [Fedora]            | [z3ntu]
![](/images/distros/opensuse.svg) [openSUSE]        | [z3ntu]
![](/images/distros/mageia.svg) [Mageia]            | [z3ntu]
![](/images/distros/solus.svg) [Solus]              | [z3ntu]

`*` Ubuntu includes flavours and derivatives, such as Linux Mint, elementaryOS, Pop!_OS and Zorin OS

[Ubuntu]: https://polychromatic.apphttps://polychromatic.app/download/ubuntu/
[Debian]: https://polychromatic.app/download/debian/
[Arch / Manjaro]: https://polychromatic.app/download/arch/
[Fedora]: https://polychromatic.app/download/fedora/
[openSUSE]: https://polychromatic.app/download/opensuse/
[Mageia]: https://polychromatic.app/download/mageia/
[Solus]: https://polychromatic.app/download/solus/

## Universal Package Formats

Polychromatic does **not** offer AppImages, Flatpaks or Snaps at the moment.

## Community Supported

Distro                  | Repository                | Maintainer
------------------------|---------------------------|-----------------------|
Gentoo                  | [vifino/vifino-overlay]   | [vifino]
Red Hat / CentOS        | [moozhub/yum-repo-mooz]   | [moozhub]

If there's a dependency or packaging problem, please raise the issue on their repository.

[OpenRazer]: https://openrazer.github.io
[lah7]: https://github.com/lah7
[z3ntu]: https://github.com/z3ntu
[vifino]: https://github.com/vifno
[moozhub]: https://github.com/moozhub
[vifino/vifino-overlay]: https://github.com/vifino/vifino-overlay/tree/master/app-misc/
[moozhub/yum-repo-mooz]: https://github.com/moozhub/yum-repo-mooz

---

## Tray Applet vs Desktop Environments

The toolkit GTK powering some desktop environments consider "system tray" to
be obsolete. As a result, the tray applet may work straight out of the box and
will need additional steps.

| Environment   | Distro Family | Notes                                           |
| ------------- | ------------- | ----------------------------------------------- |
| GNOME Shell   | ![](/images/distros/ubuntu.svg) Ubuntu   | Install [`gnome-shell-extension-appindicator`](https://packages.ubuntu.com/focal/gnome-shell-extension-appindicator) using your package manager.
| GNOME Shell   | ![](/images/distros/arch.svg) Arch       | Install [`gnome-shell-extensions-appindicator-git`](https://aur.archlinux.org/packages/gnome-shell-extension-appindicator-git/) from the AUR.
| GNOME Shell   | Other         | Install the GNOME extension that provides AppIndicator support.
| Pantheon      | elementaryOS  | [This feature was removed in 5.0 "Juno"](https://www.reddit.com/r/elementaryos/comments/8zdrvz/any_way_to_get_back_indicators_in_juno/). You can restore the feature by [following these instructions](https://www.linuxuprising.com/2018/08/how-to-re-enable-ayatana-appindicators.html).

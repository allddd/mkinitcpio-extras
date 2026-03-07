# mkinitcpio-extras

Collection of mkinitcpio hooks for busybox based initramfs.

## Installation

[mkinitcpio-extras](https://aur.archlinux.org/packages/mkinitcpio-extras) is available as a package in the AUR. For instructions on how to install packages from the AUR, see this [wiki article](https://wiki.archlinux.org/title/Arch_User_Repository) or the man page of your [AUR helper](https://wiki.archlinux.org/title/AUR_helpers).

> [!important]
> After installing the package, check optional dependencies and manually install those required by the hooks you plan to use. E.g. to use the `netconf` and `dropbear` hooks, you have to install [mkinitcpio-nfs-utils](https://archlinux.org/packages/?q=mkinitcpio-nfs-utils) and [dropbear](https://archlinux.org/packages/?q=dropbear).

## Usage

Documentation on individual hooks can be viewed using `mkinitcpio`:  

```
mkinitcpio -H <hookname>
```

## License

This project is licensed under the terms of the `GPL-2.0-only`. See [LICENSE](./LICENSE) for more details.

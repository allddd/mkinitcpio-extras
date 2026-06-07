# mkinitcpio-extras

Collection of mkinitcpio hooks for busybox based initramfs.

## Installation

[mkinitcpio-extras](https://aur.archlinux.org/packages/mkinitcpio-extras) is available as a package in the AUR. For instructions on how to install packages from the AUR, see this [wiki article](https://wiki.archlinux.org/title/Arch_User_Repository) or the man page of your [AUR helper](https://wiki.archlinux.org/title/AUR_helpers).

> [!important]
> After installing the package, check optional dependencies and manually install those required by the hooks you plan to use. E.g. to use the `dropbear` hook, you have to install the [dropbear](https://archlinux.org/packages/?q=dropbear) package.

## Usage

Documentation on individual hooks can be viewed using `mkinitcpio`:  

```sh
mkinitcpio -H <hook_name>
```

## Copyright

This project is licensed under the GNU General Public License v2.0. See [LICENSE](./LICENSE) for more details.

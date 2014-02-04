# Arch Packages

This is a repository of [Arch Linux](https://www.archlinux.org/) source
packages. Most of the packages are customised versions of those found in the
[AUR](https://aur.archlinux.org/packages).

These packages are primarily for [my](https://github.com/homme) own use but
feel free to submit pull requests to improve them.  Hopefully the resulting
packages improve on those present in the AUR where the package owners will be
able to use this resource to update their packages as they see fit.

## Usage

Clone the repo and build and install the package(s) you require using
[`makepkg`](https://wiki.archlinux.org/index.php/makepkg).  For example, to
compile `libspatialite` try:

```shell
git clone https://www.github.com/homme/arch-packages
cd arch-packages/libspatialite
makepkg -i
```

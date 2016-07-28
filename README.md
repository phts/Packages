# Sublime Packages

This is a fork of [sublimehq/Packages](https://github.com/sublimehq/Packages).
It contains some my fixes and improvements (in most cases for JavaScript and Ruby).
Also there is an enhanced "Twilight" theme which has some improvements based on the syntax changes.

---

> **These packages are developed against the latest [Sublime Text 3 Dev Build](http://sublimetext.com/3dev). Bugs may exist on older builds, and the format used is not compatible with builds older than 3092.**

## Installation

If you want to make changes to these packages and test them locally, fork this repository and then symlink the changed packages into your *Packages* folder.

*Replace `Python` in the following commands with the name of the syntax to install.*

### OS X

```bash
$ git clone https://github.com/sublimehq/Packages.git
$ ln -s `pwd`/Packages/Python ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
```

### Linux

```bash
$ git clone https://github.com/sublimehq/Packages.git
$ ln -s `pwd`/Packages/Python ~/.config/sublime-text-3/Packages/
```

### Windows

On Windows, you can use directory junctions instead of symlinks (symlinks require administrative rights; directory junctions don't):

```powershell
# Using PowerShell
PS> git clone https://github.com/sublimehq/Packages.git
PS> cmd /c mklink /J "$env:APPDATA/Sublime Text 3/Packages/Python" (convert-path ./Packages/Python)
```

Alternatively, download the portable version, and clone this repository directly as a subdirectory of the *Data* folder.

---

After you've finished, keep in mind that you're now overriding a default package. When Sublime Text updates to a new version, you'll run the risk of having an out-of-date package unless you pull the latest changes from this repository.

# Basic installation

Shell script for installation of basic programs for GNU/Linux Debian.
Based on [GUTY517](https://github.com/GUTY517/Programas-en-bash)'s script.

## Programs the script installs
	 - Dropbox
	 - VLC
	 - BleachBit
	 - GDebi
	 - GIMP
	 - KolourPaint
	 - qBittorrent **(Optional)**
	 - Oracle VirtualBox **(Optional)**
	 - LaTeX **(Optional)**
	 ----
	 Programming package **(Optional)**
	 - GNU Emacs 24
	 - Java
	 - GCC
	 - G++
	 - Haskell
	 ----
	 Security/Pentesting package **(Optional)**
	 - NMap
	 - WireShark
	 - ExifTool
	 - WiFite
### Prerequisites

- Root privileges.
- Execution permision for the file.

### Executing

Firt go to the directory which contains the file.
Say it is

```
cd ~/Bash-Programs
```

Then execute the file as super user.

```
sudo ./basicInstall
```

In case you are root execute

```
./bacisInstall
```

After the file is execute it will first ask for VirtualBox installation (Due to an addition in the source.list file). Then, it will run the command

```
apt-get update
```

After this, the script will start installing the programs listed above. Except for those marked as Optional.

Later, it will ask to install the programs marked as optional.
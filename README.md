# GNU Midnight Commander

**GNU Midnight Commander** (also referred to as **MC**) is a user shell with text-mode full-screen interface. It can be run on the OS console, in xterm and other terminal emulators.

GNU Midnight Commander allows you to manage files while making most of you screen and giving you a clear representation of the filesystem, yet it's simple enough to be run over a telnet or ssh session.

GNU Midnight Commander is released under the GNU General Public License version 3 or any later version. A copy of the file is included with this distribution package.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/mc
$ dnf install -y mc
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y mc
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/mc).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/mc) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.

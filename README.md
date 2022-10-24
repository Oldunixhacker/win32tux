# Win32Tux

Win32Tux is a WINE wrapper to run Windows apps on Linux-based systems.

## Install

Install Win32Tux by downloading and running the installer:

```bash
$ bash -c "$(curl https://win32tux.github.io/getw32tux)"
```

Output:

```
Please gain root access by entering your password.
If constant failure is encountered, you must enter the root password.

Enter your password:
```

## Uninstall

> **Note**: You must be using SystemV, `runit`, or any other `init.d`-compatible init
  system to uninstall Win32Tux. Most users use one of those,most people can ignore this message.
  
  Some SystemD installs support only `.service` files as daemons. The uninstaller is a
  daemon. In the case of SystemD, Win32Tux will use the SystemD system service folder with a `.service`.

If you don't like Win32Tux, uninstall it:

* **Win32Tux** > **Remove Win32Tux** > **Restart System**


# slstatus - suckless status
slstatus is a suckless status monitor for window managers that use WM_NAME (e.g., dwm) or stdin to fill the status bar.

## Features
- Battery percentage/state/time left
- CPU usage
- CPU frequency
- Custom shell commands
- Date and time
- Disk status (free storage, percentage, total storage, and used storage)
- Available entropy
- Username/GID/UID
- Hostname
- IP address (IPv4 and IPv6)
- Kernel version
- Keyboard indicators
- Keymap
- Load average
- Network speeds (RX and TX)
- Number of files in a directory (hint: Maildir)
- Memory status (free memory, percentage, total memory, and used memory)
- Swap status (free swap, percentage, total swap, and used swap)
- Temperature
- Uptime
- Volume percentage (OSS/ALSA)
- WiFi signal percentage and ESSID

## Requirements
Currently, slstatus works on FreeBSD, Linux, and OpenBSD.
To build slstatus, you need the Xlib header files.

## Installation
1. Edit `config.mk` to match your local setup (slstatus is installed into the `/usr/local` namespace by default).
2. Run the following command to build and install slstatus (if necessary, as root): make clean install

3. ## Running slstatus
See the man page for details.

## Configuration
slstatus can be customized by creating a custom `config.h` and (re)compiling the source code. This keeps it fast, secure, and simple.

## Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/fooBar`).
3. Commit your changes (`git commit -am 'Add some fooBar'`).
4. Push to the branch (`git push origin feature/fooBar`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Todo
- Cleaning up the whole codebase is the goal before thinking about a release.

## Troubleshooting
If you encounter any issues, check the [issues](https://github.com/aerplejn/slsproject/issues) page or open a new issue.

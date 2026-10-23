# Difference between apt update and apt upgrade

`apt update` only downloads the latest package lists from the repositories and checks for updates. It does not install or upgrade any software on the server. On the other hand, `apt upgrade` actually downloads and installs the newer versions of the currently installed packages. Therefore, we should always run `apt update` first to fetch the latest list before running `apt upgrade`.

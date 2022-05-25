<h1 align="center">SaveHabr</h1>

<p align="center">The collection of scripts for saving entries from https://habr.com.</p>

## Features:

- Save info by username.
- Save post (with comments) into the [MiceWeb](https://github.com/Robotizing/MiceWeb) Library.
- Save by lists.

---

## Installation (Linux, macOS):

Install `wget`.

Install [Wayback Machine Downloader](https://github.com/ImportTaste/wayback-machine-downloader) and [MiceWeb](https://github.com/Robotizing/MiceWeb).

---

## Installation (Windows):

Install [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (requires about 2GB disk space), [Cygwin](https://www.cygwin.com/), [Git Bash](http://git-scm.com), or some other tool that enables Bash functionality in Windows.

Follow the above section.

---

## Usage:

Open a terminal in the folder and run `./save_user` or `./save_post` with arguments.

### Save user info:
`./save_user example_nickname`

### Save post:
`./save_post 1`

`./save_post https://habr.com/post/1`

### Save all entries from users.txt or posts.txt:
`./save_users`

`./save_posts`

---

## Notes:

Each entry may contain hundreds files, that's why the scripts zip downloaded entries.

Mount zips: use [Zipster](https://ipfs.io/ipfs/QmUBbaw45ebpNB8oTPd5jR8n6v8oGJ9UMKMmnWYmX4Sk8Z) on macOS, `avfs` on Linux, some tool like `WinMount` on Windows. So, you don't have to unpack zip-files to work.

---

## Related Projects:

- [SaveSites](https://github.com/defder-su/SaveSites)

- [RatBrowser](https://ratbrowser.com)

- [IPFS](https://ipfs.io)

- [ZeroNet](https://zeronet.dev)

---

## Contact:

You are welcome in [Defder.info](https://defder.info).

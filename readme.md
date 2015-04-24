# github-backup

Deadly simple PHP script for backing up your GitHub projects.

## Installation

```shell
git clone https://github.com/bound1ess/github-backup.git
cd github-backup
chmod +x ./github-backup
sudo cp ./github-backup /usr/local/bin/github-backup
```

## Usage

```
github-backup @yourgithubnickname directorytosaveto [unpack]
```

If you specify `unpack` option, all downloaded ZIP archives will be unpacked.

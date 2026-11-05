# Contributing

Thanks for considering a contribution to `cyberpanel-cli-php-version-changer`!

## Setup

Requirements: a server (or VM) running CyberPanel, Bash, and root access. Nothing to install; it is a single script.

```bash
git clone https://github.com/kalprajsolutions/cyberpanel-cli-php-version-changer.git
cd cyberpanel-cli-php-version-changer
```

## Checks

The CI workflow runs shellcheck. Run it locally before opening a PR:

```bash
shellcheck change_php_version.sh
```

Test your change on a disposable VM or container before opening the PR. The script relinks `/usr/bin/php`, so do not test it on a production server.

## Opening a PR

1. Fork the repo and create a branch from `main`.
2. Keep the PR focused: one fix or one feature.
3. Describe what changed and why, and mention the OS you tested on.

## Reporting issues

Use the issue templates so reports arrive with the details needed. Questions are welcome in Discussions.

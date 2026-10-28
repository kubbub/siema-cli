# siema CLI

`siema` is the command-line tool for [siema-ai.pl](https://siema-ai.pl), the Polish-first
inference API: sign up, log in, manage API keys, check usage and balance, top up, file help
requests and set up coding agents, from the terminal.

This repository holds release binaries only.

## Install

macOS or Linux (amd64, arm64):

```bash
curl -fsSL https://siema-ai.pl/install.sh | sh
```

The script downloads the binary for your system from the
[latest release](https://github.com/kubbub/siema-cli/releases/latest), checks it against
`SHA256SUMS` and installs it to `~/.local/bin/siema`. Run it again to update.

By hand: download `siema-<os>-<arch>` and `SHA256SUMS` from a release, check with
`shasum -a 256 -c SHA256SUMS --ignore-missing`, `chmod +x` it and put it on your `PATH` as `siema`.

## Use

```bash
siema signup    # or: siema login
siema help
```

Docs: <https://docs.siema-ai.pl/guides/cli/>. Help: `siema ticket new` or
<support@siema-ai.pl>.

## License

Proprietary. © energiaLab. You may install and run the binaries to use siema-ai.pl.

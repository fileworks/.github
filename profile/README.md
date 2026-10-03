# Fileworks

Local-first tools for organizing media and recovering files into inspectable,
portable folders. Review the planned changes and keep independent backups.

| Tool | Purpose | Get started |
|---|---|---|
| [MediaSorter](https://github.com/fileworks/media-sorter) | Desktop photo/video organization, duplicate review and optional local AI tagging | [Public macOS/Windows installers](https://github.com/fileworks/media-sorter/releases/latest) · [Install and usage](https://github.com/fileworks/media-sorter#install) |
| [UnpackSort](https://github.com/fileworks/unpacksort) | Recover and classify files from mailboxes, folders and nested archives with provenance | [Public source installation](https://github.com/fileworks/unpacksort/blob/main/docs/install.md) · [Operating manual](https://github.com/fileworks/unpacksort/blob/main/docs/manual.md) |

MediaSorter installers bundle their runtime and media tools. See its installation
guide for platforms, checksums and the current signing status. UnpackSort source
installation requires Python 3.12+, Git and pipx; no GitHub account is needed:

```console
pipx install git+https://github.com/fileworks/unpacksort.git@v1.0.0
unpacksort --version
unpacksort --help
```

Public source access and prebuilt CLI download access are separate. The product
READMEs explain the supported routes and any authentication requirements.

These projects were developed AI-first. Contributions, verification commands and
private vulnerability reporting are documented in each repository.

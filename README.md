# Useless Gadgets

A collection of small, independent projects, included here as Git submodules.

## Projects

| Project | Description |
| --- | --- |
| [MenuClocks](https://github.com/vincy-cheng/menuclocks) | A native macOS menu bar world clock built with SwiftUI and AppKit. Requires macOS 13 or newer. |

See the [MenuClocks README](https://github.com/vincy-cheng/menuclocks/blob/HEAD/README.md) for usage, build instructions, and requirements.

## Clone

```sh
git clone --recurse-submodules https://github.com/vincy-cheng/useless-gadgets.git
cd useless-gadgets
```

If you already cloned this repository:

```sh
git submodule update --init --recursive
```

## Update MenuClocks

Each submodule is pinned to a specific commit. To use the latest commit from MenuClocks' default branch:

```sh
git submodule update --remote menuclocks
git add menuclocks
git commit -m "chore: update menuclocks"
```

Make code changes and commits in the individual project repository, then update the submodule reference here.

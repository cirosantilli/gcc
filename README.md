# GCC Hack Cheat

Small GCC patches to learn how to hack GCC.

Each branch of this repo contains a small GCC patch to learn how to hack GCC.

They are all useless and most just print the string `haked` to stdout or the current date to some file.

The goal is to learn how to hack GCC.

All branches:

- are one commit long, and applied to a GCC release tag, e.g. 5.1.0
- start with `hack/<tag>/`, e.g. `hack/5.1.0/do-something`

The default branch of this repository is `hack/main` so as to not conflict with GCC's `main` branch.

The commit message of the only commit of each branch explains what it does exactly.

Good order for you to look at the branches:

- `hack/5.1.0/gcc-main`

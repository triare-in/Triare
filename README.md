# Triare

Triare brings together the hardware and web application work for a repairable,
customizable keyboard platform. The projects are maintained as independent Git
repositories and connected here as submodules.

## Projects

| Project | Description |
| --- | --- |
| [`phantom/`](./phantom) | Keyboard hardware design files and build documentation. |
| [`WebApp/`](./WebApp) | The web application for configuring and supporting the platform. |

## Getting started

Clone this repository with its submodules:

```sh
git clone --recurse-submodules git@github.com:triare-in/Triare.git
cd Triare
```

If you already cloned without submodules:

```sh
git submodule update --init --recursive
```

Each project has its own history. Commit changes inside the relevant project,
then commit the updated submodule revision in this repository. The current
submodule revisions are local commits and must be pushed to their respective
GitHub repositories before a fresh clone can check them out.

# mcpackager

A [Taskfile](https://taskfile.dev/) template for managing add-ons in a minimalistic
way.

## Basic Usage

Copy the `Taskfile.yml` to your new project folder and configure the values in the
`env` section.

```bash
task init # generate project layout
task export # bundle add-on and import it into Minecraft
```

## Requirements

Invoke `task status` to check whether the requirements are installed.

- [Task](https://taskfile.dev/)
- [xdg-open](https://www.freedesktop.org/wiki/Software/xdg-utils/)
- [zip](https://infozip.sourceforge.net/)

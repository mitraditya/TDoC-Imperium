# TDoC - IMPERIUM

## About the project

Imperium is an indigenous Version Control System(like git) written in C++, absolutely from scratch.
It is mostly a logical approach to filesystem manipulation to emulate the basic functionalities of git. This is a project I made during [Ten Days of Code](https://10-days-of-code.netlify.app/), organised by The GNU/Linux User's Group, NIT Durgapur([@lugnitdgp](https://github.com/lugnitdgp)). You can check their Repo [here.](https://github.com/lugnitdgp/TDoC-Imperium)

## Installation

Clone the project:

```bash
git clone https://github.com/mitraditya/TDoC-Imperium.git
```

Run the following command:

```bash
cd scripts && ./build.sh

```

`build.sh` makes the project and creates an imperium folder in the `$HOME` folder. This folder will contain the compiled C++ file that is executed everytime an imperium command is called. The `imperium.sh` file is also copy pasted over to the folder for convenience. After the files are copied, the `imperium.sh` file is sourced to the `~/.bashrc` file so that its functions can be called from any directory.

## Usage

Create or move to an existing directory and type `imperium init` to initialize an imperium repository. Now you can play around with the commands listed below

```bash
imperium add [file/directory/.]
imperium commit "[message]"
imperium log
imperium checkout [hash]
imperium status
imperium revert [hash]
imperium resolve
imperium stash
imperium stash apply
imperium rm --cached [file/directory/.]
imperium rm -r [directory]
imperium rm [file]
```

## How to Contribute

- Fork the repository.
- Improve current program by:
  - Improving functionality.
  - Adding new feature.
- Push your work in a new branch and Create a Pull Request.

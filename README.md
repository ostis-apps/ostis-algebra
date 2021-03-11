# OSTIS-Algebra

Main repository for OSTIS Numeric models system.

## Installation

Linux:

```sh
git clone https://github.com/ostis-apps/ostis-algebra
cd {project-name}/scripts
./prepare.sh
```

## Build knowledge base

Linux:

```sh
cd {project-name}/ostis-web-platform/scripts
./build_kb.sh
```

## Run

Run on Linux:

```sh
#Terminal 1
cd {project-name}/ostis-web-platform/scripts
./run_sctp.sh

#Terminal 2
cd {project-name}/ostis-web-platform/scripts
./run_scweb.sh
```

Then open localhost:8000 in your browser.

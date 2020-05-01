# Workstation Setup

This project automates the process of setting up a new Pivotal machine using a simple [Bash](https://www.gnu.org/software/bash/) script.

Open up Terminal.app and run the following commands:

```sh
mkdir -p ~/workspace
cd ~/workspace
git clone https://github.com/pivotal/workstation-setup.git
cd workstation-setup
```

### James Machine

If you're setting up an engineering machine choose which languages to install:

```sh
./setup.sh james
```

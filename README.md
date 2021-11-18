# P4lang - Bootstrap

The script is only for ubuntu 20.04, and the installation is **irreversible**, do it in a virtual machine!

I have tested it with official ubuntu image ([tw](https://www.ubuntu-tw.org/modules/tinyd0/), [en](https://ubuntu.com/download/desktop)) on 2021-11-18, systems from unknown sources may fail.

## Quick Start

Type in the following commands in a virtual machine with ubuntu 20.04 to setup P4 environment

```sh
sudo apt update
sudo apt install -y curl
curl -sL https://raw.githubusercontent.com/doraeric/p4lang-bootstrap/main/install.sh | sudo sh
```

## Tutorial

Get P4 [tutorials](https://github.com/p4lang/tutorials) with the following command
```sh
git clone https://github.com/p4lang/tutorials.git
```

# Vagrant Ubuntu gRPC C++ VM

This repository provides a Vagrant configuration for quickly provisioning an Ubuntu 22.04 virtual machine with gRPC and Protocol Buffers (protoc) for C++ development. It automates the setup of all required dependencies, builds gRPC and protoc from source, and is ideal for C++ developers who want a reproducible environment for gRPC projects.

## Features
- Ubuntu 22.04 LTS base box
- Automatic installation of build tools and dependencies
- Builds and installs gRPC and Protocol Buffers (protoc) for C++
- SSH access via `vagrant ssh`

## Usage
1. Clone this repository.
2. Run `vagrant up` to provision the VM.
3. SSH into the VM with `vagrant ssh`.
4. Start developing C++ gRPC applications!

## Notes
- The `.vagrant` directory and all log files are excluded from version control via `.gitignore`.
- You can customize the provision script in the `Vagrantfile` as needed for your project.

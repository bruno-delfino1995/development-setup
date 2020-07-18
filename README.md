# Development Setup

## Installation

This is supposed to be installed on top of [Arch Linux](https://www.archlinux.org/).

To start the installation you just run `./setup`. If there's a missing dependency, you'll be properly instructed on how to install it.

## Contributing

This project consists of an Ansible Playbook with tools separated with rules based on their usage. We try to minimize the tools and don't expect the submission of personal usage tools, like antibody and oh-my-zsh. We focus on tools used within scripts and across the organization. However, this doesn't mean that you cannot introduce a new tool, check for existing tools before adding a new.

An example of contribution would be the inclusion of [vegeta](https://github.com/tsenart/vegeta) to be used as the standard tool HTTP server load testing. On the other hand, we wouldn't accept something like [fzf](https://github.com/junegunn/fzf) because we've already chosen [skim](https://github.com/lotabout/skim) to support the evolution of the Rust Ecosystem.

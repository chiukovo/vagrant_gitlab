## Installation

1. Clone this repo
1. Install [Vagrant](http://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/)
1. `vagrant up`
1. `vagrant ssh`

This will create a ubuntu virtual machine with gitlab running. By default, web port forwards to `8080` and ssh port forwards to `8022`. You can change that in [Vagrantfile](Vagrantfile#L26~L27).

## Customization

### ip

Change `config.vm.network "private_network", ip: "33.33.33.33"`

Without a valid hostname, your mail sent to Gmail will be blocked.

## Start

`http://33.33.33.33`

Username | Password
---------|-----------
root     | 5iveL!fe

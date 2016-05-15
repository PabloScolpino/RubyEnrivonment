# RubyEnvironment
A vagrant file tailored to get started with ruby development with minimum manual intervention

# Requirements
* Bash-like interpreter
* Vagrant
* VirtualBox

# On Windows

* Install [cygwin](https://www.cygwin.com/)

* Install packages in cygwin
  * bash
  * git
  * rsync

* Install apt-cyg
  * lynx -source rawgit.com/transcode-open/apt-cyg/master/apt-cyg > apt-cyg
  * install apt-cyg /bin

* Install [Vagrant](https://www.vagrantup.com/downloads.html)

* Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

* Clone this repository
  * git clone https://github.com/PabloScolpino/RubyEnrivonment.git

* Launch the machine
  * vagrant up
  * If you experience an error during machine creation check out [this vagarnt bug](https://github.com/mitchellh/vagrant/issues/6702)

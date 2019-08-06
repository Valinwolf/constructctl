# NO LONGER IN DEVELOPMENT
I was unable to get Construct properly working under Fedora 29 x86_64 on a DigitalOcean VPS. This script worked, however Construct did not. Matrix was something I was wanting to use, however I could not use Synapse due to the resource requirements and I spent over a week trying to get Construct working properly without any luck. One thing fixed, two things broke. As such I am moving on to a different decentralized protocol. Perhaps I will eventually get it working and I will resume developement of this script, but I will wait for Construct to become more mature.


This repository is for a control script that will install/update, start, stop, restart, reset your Construct server. Note this script is designed with ***Fedora*** in mind.

## Installation
The `cURL` method
`bash <(curl -s 'https://raw.githubusercontent.com/Valinwolf/fabricator/master/install')`
The `WGet` method
`bash <(wget -qO- 'https://raw.githubusercontent.com/Valinwolf/fabricator/master/install')`

## Usage
#### Implemented Commands
`start` _takes 0 arguments_
>Start the Construct daemon

 

`stop` _takes 0 arguments_
>Stop the Construct daemon

 

`restart` _takes 0 arguments_
>Restarts the Construct daemon if it is running or starts it if it is not

 

`update` or _takes 0 or 1 arguments_
>Updates or installs the Construct daemon
>
>_**Note:** When installing for the first time, use `install` so it installs the dependencies too._

 - _arg1: \[Optional] If included, the value must be `--debug` and will enable a debug build_

 

`install` _takes 0 or 1 arguments_
>Installs the Construct daemon and all it's dependencies

 - _arg1: \[Optional] If included, the value must be `--debug` and will enable a debug build_

 

`reset` _takes 0 arguments_
>Wipes all server config

 

`set` _takes 2 arguments_
>Sets a variable important to the install, update, or launching of Construct

 - _arg1: Name of the variable to be changed_
 - _arg2: Value to change the variable to_

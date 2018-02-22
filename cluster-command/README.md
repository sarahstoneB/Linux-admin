# cluster-command

#### WARNING: These instructions are incomplete. Consider them as notes quickly drafted on a napkin rather than proper documentation!

cluster-command is a bash script that loops through a list of hosts found in cluster-command.txt file. 

## Install

To install, change to the directory you want to download the script and host file.

    curl -L https://api.github.com/repos/BradleyA/Linux-admin-scripts/tarball | tar -xzf - --wildcards */cluster-command.* ; mv BradleyA-Linux-admin-scripts-*/cluster-command/cluster-command.* . ; rm -rf BradleyA-Linux-admin-scripts-*

## Clone

To clone, change to the directory you want to download the script, README, and host file. Use git to clone these files into your directory. If you do not have git then enter; "sudo apt-get install git". On the github page of this script use the "HTTPS clone URL" with the 'git clone' command.

    git clone https://github.com/BradleyA/Linux-admin-scripts
    cd Linux-admin-scripts/cluster-command

#### WARNING: These instructions are incomplete. Consider them as notes quickly drafted on a napkin rather than proper documentation!

## Usage
    cluster-command.sh require-reboot

## Output
    _____

#### System OS script tested
 * Ubuntu 14.04.3 LTS
 * Ubuntu 16.04.3 LTS (armv7l)

#### Design Principles
 * Have a simple setup process and a minimal learning curve
 * Be usable as non-root
 * Be easy to install and configure

## License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
     ______      _  ________ _   _ ______ _______     _   _  _____
    |  ____/\   | |/ /  ____| \ | |  ____|__   __|   | \ | |/ ____|
    | |__ /  \  | ' /| |__  |  \| | |__     | |______|  \| | |  __
    |  __/ /\ \ |  < |  __| | . ` |  __|    | |______| . ` | | |_ |
    | | / ____ \| . \| |____| |\  | |____   | |      | |\  | |__| |
    |_|/_/    \_\_|\_\______|_| \_|______|  |_|      |_| \_|\_____|

           D   O   C   U   M   E   N   T   A   T   I   O   N

FakeNet-NG 3.3 is a next generation dynamic network analysis tool for malware
analysts and penetration testers. It is open source and designed for the latest
versions of Windows (and Linux, for certain modes of operation). FakeNet-NG is
based on the excellent Fakenet tool developed by Andrew Honig and Michael
Sikorski.

The tool allows you to intercept and redirect all or specific network traffic
while simulating legitimate network services. Using FakeNet-NG, malware analysts
can quickly identify malware's functionality and capture network signatures.
Penetration testers and bug hunters will find FakeNet-NG's configurable
interception engine and modular framework highly useful when testing
application's specific functionality and prototyping PoCs.

Installation
============

Due to the current FakeNet-NG is only for python with lower version, this 
FakeNet-NG is modified for newer version of python. The current test for 
this is on the python 3.12 with Ubuntu 24.04.1 LTS


Installing module
-----------------
Installation on Linux requires the following dependencies:
 * Python pip package manager (e.g. python-pip for Ubuntu).
 * Python development files (e.g. python-dev for Ubuntu).
 * OpenSSL development files (e.g. libssl-dev for Ubuntu).
 * libffi development files (e.g. libffi-dev for Ubuntu).
 * libnetfilterqueue development files (e.g. libnetfilter-queue-dev for
   Ubuntu).

Install these dependencies using the following command:

    sudo apt-get install build-essential python-dev libnetfilter-queue-dev

Obtaining the latest source code and installing it manually:

    git clone https://github.com/mandiant/flare-fakenet-ng/

Change directory to the downloaded flare-fakenet-ng and run:

    sudo python3 pip install . --break-system-packages

Usage:
    
    sudo fakenet

Note: 

    - If it said used port 53, please check port 53 is opened or not
    - Please run as sudo if it not having privilledge
    - If any bug appear, please open issues :((((( 

Note: other like how to use or User Interface, Simple run, please go to https://github.com/mandiant/flare-fakenet-ng/ to see

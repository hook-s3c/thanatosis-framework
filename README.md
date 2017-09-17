# thanatosis-framework
thanatosis - noun, (of an animal) the ability to fake death in order to evade a predator or any other unwelcome intrusion.

## Greetz

shouts to sh3llg0d, an0n_l1t3, daemochi, akatz!!!!

## Overview

When joining a network, your machine is liable to give you up.

Thanatosis works in order to make sure you appear deathly silent on the nework, 

The monitoring/evasion tool audits packets on the wire and alerts you for leaks and intrusions.

## Goals

- Validates integrity by running tests
- Audits the line for broadcast traffic
- Alerts for running services
- Alerts for intrusion detection (someone is attempting to scan you)
- Disables connection upon intrusion
- Detects MITM / ARP-poisoning
- MAC-changer auditing and monitor
- Ensures VPN is active, always
- Profile management
- Gnome extension

## Quickstart

```
git clone https://github.com/hook-s3c/thanatosis-framework
cd ./thanatosis-framework
sudo chmod +x ./thanatosis.py
pip install -r ./requirements.txt

./thanatosis.py
```


## Requirements

```
apt-get install wireshark
apt-get install tshark
apt-get install ufw
apt-get install gufw
```

## Unit tests

### Running the tests


### Notes

- Unit test coverage

### References

- https://github.com/KimiNewt/pyshark
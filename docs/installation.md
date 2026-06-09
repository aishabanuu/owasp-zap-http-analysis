# Installation Guide

## Environment

- MacBook Air M1
- VMware Fusion
- Kali Linux ARM64
- Mozilla Firefox
- OWASP ZAP

## Update Kali

bash sudo apt update sudo apt upgrade -y 

## Install OWASP ZAP

bash sudo apt install zaproxy -y 

Verify installation:

bash which zaproxy 

Launch:

bash zaproxy 

## Install Firefox

bash sudo apt install firefox-esr -y 

## Verify Internet Connectivity

bash ping -c 4 google.com 

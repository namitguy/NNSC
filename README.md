# Namibia National Cybersecurity 8th Competition

## Introduction

This is a list of tools I've found useful in the past when testing systems.

## Discovery

**Nmap**

Nmap is used to discover hosts and services on a computer network by sending packets and analyzing the responses. Nmap provides a number of features for probing computer networks, including host discovery and service and operating system detection.

https://nmap.org/download

**Tenable Nessus Essentials**

This free version of a vulnerability assessment solution includes remote and local (authenticated) security checks. Limited by default to 16 hosts.

https://www.tenable.com/products/nessus/nessus-essentials

**Purple Knight**

Purple Knight is a standalone utility that queries the Active Directory and Azure AD environment and performs a set of tests against many aspects of Active Directory’s security posture, as an attacker would see it

https://www.purple-knight.com/resources/

## Exploiting

**MetaSploit Framework**

The Metasploit Project is a computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development. The world's most used penetration testing framework.

Installation via Windows:
https://windows.metasploit.com/metasploitframework-latest.msi

Installation via Linux:
https://trendoceans.com/metasploit-framework-on-linux/

$ sudo apt install curl  #Installing curl for Debian, Ubuntu, Linux Mint, Pop!_os
$ sudo dnf install curl  #Installing curl for Arch, Manjaro, EndeavorOS
$ sudo pacman -Sy curl   #Installing curl for RHEL, Fedora, Alma Linux

$ curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && chmod 755 msfinstall && ./msfinstall

**Kali Linux Penetration Testing Platform**

Kali Linux contains several hundred tools targeted toward various information security tasks, such as penetration testing, security research, computer forensics, and reverse engineering.

https://www.kali.org/

**PsExec**

PsExec is a light-weight telnet-replacement that lets you execute processes on other systems, complete with full interactivity for console applications, without having to manually install client software

https://learn.microsoft.com/en-us/sysinternals/downloads/psexec

## Tools

**VMware Player**

This tool runs a single virtual machine on a Windows or Linux PC. It can be used when setting up an environment to analyze malware.  Useful to deploy a VM without AV for your toolkit or to run Kali.

https://www.vmware.com/products/workstation-player/workstation-player-evaluation.htm

**VirtualBox**

An Open Source alternative to VMware Player. VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use.  Useful to deploy a VM without AV for your toolkit or to run Kali.

https://www.virtualbox.org/wiki/Downloads

**MetaSploitable**

Metasploitable3 is a VM that is built from the ground up with a large amount of security vulnerabilities. It is intended to be used as a target for testing exploits with metasploit

https://app.vagrantup.com/rapid7/boxes/metasploitable3-win2k8


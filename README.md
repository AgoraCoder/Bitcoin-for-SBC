Bitcoin-for-SBC
===============

All-in-one script for generating, printing, initializing, splitting, signing and restoring Bitcoin software, hardware and multisig wallets on a Single Board Computer.

After successful installation and test vectors, you can disable online access and remain air-gapped for subsequent use.

After generating / restoring bitcoin seeds, should you want to update libraries, the safest option would be to format and wipe your SD/MicroSD/EMC module, reinstall the OS, and start afresh.

Alternatively you could purchase a new flash memory card and reinstall

**Note : this installation takes approx 200Mb download and >1 hour duration**

# Intended Audience

Bitcoiners with an interest in security, who want a cheap simple  and secure cold offline airgapped environment to generate bitcoin seeds, sign transactions, and test/restore mnemonics.

# Examples

	* Generating BIP38 paper wallets with bitaddress
	* Initializing and restoring TREZOR
	* Initializing and restoring HW-1 / Ledger Nano
	* Test restoring a BIP39 mnemonic on an airgapped machine
	* Upgrading/Downgrading TREZOR firmware
	* Generating a Armory wallet offline, exporting/printing the backup, and exporting the watch only "online" wallet for generating transactions

# Environment / OS
Pi B/B+ : NOOBS Raspian (source)

Beaglebone Black rev C : OS (source)

Piper 1.12 ISO (source)

# Why

# Getting Started

	* OS installation
	* Internet
	* Camera setup
	* Overclocking Pi

# Script Functions
* Bitcoin-for-SBC script
	* **Run ALL installation steps - no confirmation prompts (recommended)** *or*
	* Setup and Repo update
		*	update Raspian/Debian
	* Installation core apps
		* install Trezor + Libs
		* install BTChip + Libs
		* install Electrum 2 + Libs
		* install Armory + Libs
	* Optional installation of non-core apps
		* install Bitaddress
		* install Coinkite + BitMEX signing beta tools
		* download Trezor firmwares
		* Install BIP39 scripts
		* Install pybitcointools
	* Optional helper packages
		* install QR Code Libs
		* install ImageMagick
		* install Shamir's Secret Sharing Scheme
		* Install PassGuardian
		* Install GreenAddress
		* Install Chromium and Iceweasel
	* Maintenance
		* Test installation vectors
		* Upgrade all packages
		* Installing Raspberry Pi camera(source) QR reading importing support
	* Special functions
		* Make QR codes for cold wallet use

# ToDo
		* ? CUPS / CUPS PDF for print to PDF function ?
		* Text font for Command Line such that QR codes are displayed properly
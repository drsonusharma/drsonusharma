---
layout: post
title: Solved errors were encountered while processing grub efi amd64 signed
category: [howto]
---
![linux](/assets/featured/linux.png "linux")

## Execute commands below to solve this problem

	sudo apt-get purge grub\*
	sudo apt-get install grub-efi
	sudo apt-get autoremove
	sudo update-grub

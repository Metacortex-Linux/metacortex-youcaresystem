# metacortex-youcaresystem

uCareSystem is an all in one system app which offers an easy to use application to automatically check updates, install updates, remove junk files and clean used space.

All-in-one System Update and maintenance app. This simple script will automatically refresh your packagelist, download and install software updates (if there are any), remove old kernels, obsolete packages and configuration files and free up disk space without any user intervention.

## Description:

In summary, youcaresystem automatically performs the following maintenance processes without any need of user interference :

- Updates the list of available packages
- Downloads and installs the available updates
- Checks if there are older Linux kernels on the system and removes them. However it keeps the current and one previous version of the kernel.
- Cleans the cache of the downloaded packages
- Removes obsolete packages
- Removes orphan packets
- Deletes package configuration files from packages that have been uninstalled by you.

## Usage

YouCareSystem creates an launcher icon in your Applications menu. When you click it, it performs the default maintenance by automatically launching a terminal. 

Alternativelly, you can invoke it throu terminal with variours parameters/ flags. The default system updates and maintenace for Ubuntu / debian / Linux Mint (and derivatives) :

	sudo youcaresystem

When the next available release is availabe for Ubuntu (and official flavors) you can upgrade with '-u':
	
	sudo youcaresystem -u

If you are a tester, developer, or simply an enthusiast, you can upgrade to the next development cycle of Ubuntu (and official flavors) with '-d':

	sudo youcaresystem -d

If your Ubuntu (and official flavors) has reached the EOL support you can upgrade to the next supported release with '-eol':
	
	sudo youcaresystem -eol

For information about all the availabe parameters / flags, start ucaresystem-core with '-h' parameter :

	sudo youcaresystem -h

# brackets-debian-8-jessie
this fixes some shit of brackets for Debian 8 Jessie e.g. libcrypt20

~I'll upload it tomorrow or tomorrowow or tomorrowowowow. Or whenever I have the time


# Update
I just fixed the libcrypt thing and uploaded everything.
How to install this version of brackets:

Install git via apt
**sudo apt-get install git**

Clone the repository
**git clone https://github.com/xpfi/brackets-debian-8-jessie.git**

Change the ownership of all files & folders to root (For deb packaging purposes)
**sudo chown -R root:root brackets-debian-8-jessie/**

Create a .deb file
**sudo dpkg-deb --build brackets-debian-8-jessie/**

Install the .deb-File
**sudo dpkg -i brackets-debian-8-jessie.deb**

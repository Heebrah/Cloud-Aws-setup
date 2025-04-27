# Cloud-Aws-setup
## introduction to linux

Linux
Linux is an open-source operating system based on UNIX. It manages hardware and software resources and provides services for computer programs. Linux is known for its stability, security, and flexibility. It is widely used in servers, desktops, mobile devices (like Android), and embedded systems.

Types of Linux
Linux comes in many versions, called "distributions" (distros). Common types include:

✅Ubuntu – user-friendly, great for beginners.

✅Fedora – cutting-edge features and technologies.

✅CentOS/Red Hat – stable and enterprise-focused.

✅ Debian – highly stable and versatile.

✅ Arch Linux – lightweight and customizable for advanced users.

## creating an Ec2 instance
This is searching the EC2 on the search box and click in then you will see instance click and go to create install. Then you name your instance and create a key then run your instance.

https://imgur.com/UhvFSXg

## Creating a key
this is a key that is used to verify a server before it can run.
in my case i choose RSA as the key

https://imgur.com/OK7OseX

## locate the key file on mobaxterm
mobaxterm is a tool which allows us to use linux access on window

https://imgur.com/yHQ1JPa

## using ssh to log into the instance
To log into an instance we use the command ssh -i key-name linux-os@public_ip

key-name is the we downloaded
linux-os is the server we chose like ubuntu, red-hat etc

public_ip this is shown in the instance details.

after logging in it display showing the private_ip

https://imgur.com/JAScgQb

## update app
sudo apt update_ is used to update the os

https://imgur.com/SrweHcu

## install tree

sudo apt install tree - this is a tool command that display the sub-folders in a directory 

https://imgur.com/2ltG0RE

## check the install tree
we can use tree like tree /bin where /bin is the location of the file

https://imgur.com/2FMUN3V


## upgrade app
sudo apt upgrade this is to upgrade to a newer version

https://imgur.com/SWnkPrL

## remove tree
sudo apt remove is used to remove an installed app.
like using sudo apt remove tree. get rids of the installed tree

https://imgur.com/8FtHgZF
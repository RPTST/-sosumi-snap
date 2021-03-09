# -sosumi-snap

sudo snap install sosumi --edge

xhost

xhost local:

xhost localhost

sosumi

nano ~/snap/sosumi/common/launch

Add 8G to memory

Add 4 cores to CPU


# Clover Bootloader on Sosumi VM

If all goes well soon, you will see the Clover bootloader, just press the button Enter to start macOS startup.

Note: To release the mouse pointer or remove it and focus it on the host operating system, press CTRL + Alt + G simultaneously.


# MacOS utilities

If you are a macOS user, you already know what to do next, but if not, we first create a Disk partition to install on macOS on Linux VM. Select the Disk Utility option.

# Apple disk partition

Select the first partition created by the Sosumi script which will be 68.72 GB, enough to start. Now click on To erase button given in the top menu.

# Format the disk in the extended operating system (journaled)

Just give a name to the disc while leaving the other options as is, click on the Clear button. 

When finished, close Disk Utility and return to the macOS Utilities screen.

# Reinstall macOS

Like here, we show the system that we are not installing macOS from scratch, rather assume there is a problem and we want to reinstall a new copy of macOS, which is why we have the “Reinstall macOS“, So simply select this option and press Continue button.

Click it Agree button.

# Select the disc

The disc we created above will appear in this step, select it and press the Install to get macOS on the Linux virtual machine.

So, now, if all goes well, it will settle in about 50 minutes and if not, I don’t even know how long it would take, because in my case, first of all, it showed 23 minutes over 11 hours.

It was a bit stuck here. I even browsed the Sosumi developer page but I didn’t find any relevant way to solve this problem, so in my case, I couldn’t install it. I know that running macOS on hardware and the environment, which is not the case, is always tedious work.

So that was my predicament, however, if you have a little time and want to experience it, you can try Sosumi on your machine may work properly in your case. However, I will also try the source of this snap package VM which is macOS-Simple-KVM, a set of tools to configure a fast macOS VM on QEMU, accelerated by KVM and I will let you know my experience with it . So be safe and keep experimenting with Linux.

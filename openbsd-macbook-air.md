# Context
I have an old MacBook Air 2013 lying around doing nothing, so I thought I would put it to work. It has 8 GB RAM and an Intel Core i5-4250 CPU at 1.30 GHz. MacOS is no longer supported on this old machine, so I thought it might be a good opportunity to put OpenBSD on it to bring it to life!

Unfortunately the laptop's wifi NIC was no longer working, so I had to install and external one. I googled around a bit and worked out that the TP-LINK TL-WN821N ([https://man.openbsd.org/urtwn.4](urtwn)) based on the RealTek RTL8192EU chipset is a good fit. It only cost about USD 10 on Amazon to order and luckily arrived the next day.

I downloaded install73.img from the ftp.openbsd.org and ``dd```'ed the image onto a disk using ``dd if=install73.img of=/dev/sd1 bs=1M`` and I was now ready to install. 

# Installation
I am not going to go through all the installation steps, but I can report that installation went as expected. I used whole disk GPT and used the automatic partitioning layout proposed by OpenBSD. The installer automatically configured the kernel with the right drivers for the 


# Configuration

# Performance

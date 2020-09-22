![NexMon logo](https://github.com/seemoo-lab/nexmon/raw/master/gfx/nexmon.png)


This branch adds support to the <B>libnexmon.so</B> preload shared library for the <I>SIOCSIWFREQ</I> and <I>SIOCGIWFREQ</I> ioctl() calls, which are used by some programs to <B>S</B>et or <B>G</B>et the the <B>W</B>ireless <B>FREQ</B>uency (and/or channel).
<P/>
Programs which use ioctl() calls will now be able to change the channel of supported broadcom devices.  This does NOT affect programs that use libnl/netlink to manage channels.
<P/>
The <A HREF="builds">builds</A> folder contains pre-compiled binaries for your device.  Be sure to choose the appropriate architecture.


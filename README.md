# Remote control codes for Peachtree nova65SE Amplifier

On newer Linux kernels IR support is built in and you can use

**ir-ctl -k nova65se.toml -K KEY_POWER**

On older systems you need to install **lirc** and put **nova65se.lircd.conf** in the lirc directory and then run

**irsend SEND_ONCE nova65se KEY_POWER**

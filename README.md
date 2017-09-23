### Notes

Binaries of demos I wrote between 1995 and 1998, saved thanks to scene.org.

You can run everything today in DosBox.

#### Obez (1995)

64kb intro with real-time software phong rendering.

<img src="https://raw.github.com/thbar/demomaking/master/extracts/Obez-Blue-Short.gif"></img>

The sound is buggy for historical reasons (notes with pitch too high are peaked to a lower pitch, and tempo sync is broken), but I will attempt to fix this.

#### Nikki (1996-1998)

If you run it, run the 1996 version which is properly tempo synced.

The 1996 version required a Gravis UltraSound and was perfectly synced.

The 1998 version was a re-release with a different sound player supporting the increasingly more widespread SoundBlaster, but it introduced bugs in sound sync.

### Practical notes

#### Downloads

* [Tested with DOSBox 0.74](https://www.dosbox.com/download.php?main=1)
* [Could also work with DOSBox-X](http://dosbox-x.com/)

#### How to configure DOSBox

Configuration file can be found [here](http://www.dosbox.com/wiki/Dosbox.conf#Mac_OS_X).

In `~/Library/Preferences/DOSBox\ 0.74\ Preferences`, put:

```
[autoexec]
# Lines in this section will be run at startup.
# You can put your MOUNT lines here.
KEYB FR
MOUNT D: ~/git/demomaking
```

### Things I want to do

- Unpack and disassemble Obez (tricky)

### Potentially interesting links

* [Eric Fry's IDA/DOSBox debugger plugin](https://github.com/wjp/idados)
* [HexRays debugging / decompiling tools](https://www.hex-rays.com/index.shtml)

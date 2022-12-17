# Alternative culfw for cul devices

## Note

This fork of a-culfw contains some cherry picks in order to make the project compilable again.

If you found this repository through Google, because you tried compiling the original a-culfw project and got erros like the one below, give this fork a try.

```
/usr/local/Cellar/arm-none-eabi-gcc/10.3-2021.07/gcc/bin/../lib/gcc/arm-none-eabi/10.3.1/../../../../arm-none-eabi/bin/ld: section .ARM.exidx LMA [000000000011c47c,000000000011c483] overlaps section .relocate LMA [000000000011c47c,000000000011c9eb]
collect2: error: ld returned 1 exit status
make[1]: *** [CUBE_BL.elf] Error 1
make: *** [CUBE_BL] Error 2
```
___
**The original fimware is cloned from www.culfw.de (thanks for the work to R.K.)**

**This alternative firmware has additional send receive methods and code cleanups.**
_The compiled firmware can be found at [MediaFire](https://www.mediafire.com/folder/iuf7lue8r578c/a-culfw)_

# .Shaiya

## Home directory: shaiya

1. Create tar file
*	tar cjf - [files..] | openssl des3 -salt | dd of=shaiya.tar.bz2

2. Decompressing tar file
*	dd if=shaiya.tar.bz2 | openssl des3 -d | tar jxf -

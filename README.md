# i like to code

![Top Languages](https://stats.willyyy.me/api/top-langs/?username=xDefyingGravity&layout=compact&hide=html,javascript,css&langs_count=10&theme=tokyonight&cache=2)

```asm
    .section __TEXT,__text
    .global _main
_main:
    mov x0, 1
    adrp x1, msg@PAGE
    add x1, x1, msg@PAGEOFF
    mov x2, 4
    ldr x16, =0x2000004
    svc 0
    mov x0, 0
    ldr x16, =0x2000001
    svc 0
    .section __DATA,__data
msg:
    .ascii "bye.\n"
```

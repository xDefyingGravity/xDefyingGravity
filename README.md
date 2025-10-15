# i like to code

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=xDefyingGravity&layout=compact&hide=html&langs_count=8&theme=tokyonight)

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

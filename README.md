# Prueba-uwu

jdvbsdjvnsvn
sdgwrgrsdfgds
sgdhdthrsthdf


# Cheatsheet

| Mnemonico | Operando | Breve descripción |
| --- | --- | --- |
| ASR, ASRS | Rd, Rm, <Rs|#n> | Arithmetic Shift Right |
| LSL, LSLS | Rd, Rm, <Rs|#n> | Logic shift left  |
| MUL, MULS | {Rd,} Rn, Rm | Multiply, 32-bit result |
| SUB | SUB Rd, Rn, <op2> |  |

### 2.Resta

**Código ejemplo en c**

```c
int x=30, y=4;
```

**Código resultado**

```nasm
movs    r3, #21
```

```c
int x=30, y=4;
int z=x-y;
```

```nasm
movs    r3, #30
movs    r3, #4
subs    r3, r2, r3
```

```c
int x=30;
int z=x-4;
```

```nasm

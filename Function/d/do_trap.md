# Function: <code>do_trap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, siginfo_t * info)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579037712,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:245",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037712,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, siginfo_t * info)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033808,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:232",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033808,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, siginfo_t * info)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033536,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:232",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033536,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, siginfo_t * info)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579027744,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:267",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027744,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, siginfo_t * info)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029408,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:252",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029408,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, siginfo_t * info)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:252",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033600,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071579037372,
      "name": "do_trap.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038592,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:244",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038592,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046256,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:245",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046256,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048496,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:245",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048496,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:152",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058736,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071579060065,
      "name": "do_trap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:156",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061296,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071591244557,
      "name": "do_trap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:156",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068048,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071591188261,
      "name": "do_trap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:156",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089328,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071592051516,
      "name": "do_trap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:158",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579117520,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071593818131,
      "name": "do_trap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579157088,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:160",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157088,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159248,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:160",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159248,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188560,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:149",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188560,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void do_trap(struct pt_regs * regs, int signo, int code, long unsigned int addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271346920,
      "name": "do_trap",
      "external": true,
      "loc": "arch/riscv/kernel/traps.c:59",
      "file": "arch/riscv/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/fault.c:do_page_fault",
        "arch/riscv/mm/fault.c:do_page_fault",
        "arch/riscv/mm/fault.c:do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271346920,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048848,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:245",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048848,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981984,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:245",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981984,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048432,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:245",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048432,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```

```json
{
  "name": "do_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052208,
      "name": "do_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:245",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052208,
      "name": "do_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sicode</code>
</li>
<li>
<b>Param added. </b>
<code>void * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>siginfo_t * info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void do_trap(int trapnr, int signr, char * str, struct pt_regs * regs, long int error_code, int sicode, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int signo</code>
</li>
<li>
<b>Param added. </b>
<code>int code</code>
</li>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>int signr</code>
</li>
<li>
<b>Param removed. </b>
<code>char * str</code>
</li>
<li>
<b>Param removed. </b>
<code>long int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>int sicode</code>
</li>
<li>
<b>Param reordered. </b>
<code>trapnr, signr, str, regs, error_code, sicode, addr</code> ➡️ <code>regs, signo, code, addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>void * addr</code> ➡️ <code>long unsigned int addr</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

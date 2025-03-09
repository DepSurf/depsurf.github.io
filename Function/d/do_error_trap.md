# Function: <code>do_error_trap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038688,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:280",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_divide_error",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_alignment_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038688,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034848,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:265",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034848,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034656,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:265",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034656,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028080,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:300",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028080,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030528,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:285",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030528,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579035264,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:285",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579035264,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579039648,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:262",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579039648,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047312,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:263",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047312,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049552,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:263",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049552,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579059728,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:169",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059728,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061680,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:173",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061680,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068768,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:173",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068768,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089920,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:173",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089920,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579118656,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:175",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118656,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158160,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:177",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158160,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160320,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:177",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160320,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579189632,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:166",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579189632,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049904,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:263",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049904,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578982832,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:263",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982832,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049488,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:263",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049488,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```

```json
{
  "name": "do_error_trap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053280,
      "name": "do_error_trap",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:263",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_alignment_check",
        "arch/x86/kernel/traps.c:do_stack_segment",
        "arch/x86/kernel/traps.c:do_segment_not_present",
        "arch/x86/kernel/traps.c:do_invalid_TSS",
        "arch/x86/kernel/traps.c:do_coprocessor_segment_overrun",
        "arch/x86/kernel/traps.c:do_invalid_op",
        "arch/x86/kernel/traps.c:do_overflow",
        "arch/x86/kernel/traps.c:do_divide_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053280,
      "name": "do_error_trap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void do_error_trap(struct pt_regs * regs, long int error_code, char * str, long unsigned int trapnr, int signr, int sicode, void * addr)
```
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

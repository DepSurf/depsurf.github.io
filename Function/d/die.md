# Function: <code>die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050096,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:306",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050096,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046336,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:319",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046336,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579045392,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:285",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045392,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579037984,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:287",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037984,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046176,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:349",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046176,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049408,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:407",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049408,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054384,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:398",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054384,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062160,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:398",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062160,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064256,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:403",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064256,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072240,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:422",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072240,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076464,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:439",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076464,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083408,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:439",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083408,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106368,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:439",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106368,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136992,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:433",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136992,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180464,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:439",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180464,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183856,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:442",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183856,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213072,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:442",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213072,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void die(const char * str, struct pt_regs * regs, int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490240272,
      "name": "die",
      "external": true,
      "loc": "arch/arm64/kernel/traps.c:177",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/fault.c:die_kernel_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490240272,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void die(const char * str, struct pt_regs * regs, int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224433364,
      "name": "die",
      "external": true,
      "loc": "arch/arm/kernel/traps.c:347",
      "file": "arch/arm/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/traps.c:bad_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224433364,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282346464,
      "name": "die",
      "external": true,
      "loc": "arch/powerpc/kernel/traps.c:286",
      "file": "arch/powerpc/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:kernel_bad_stack",
        "arch/powerpc/kernel/traps.c:unrecoverable_exception",
        "arch/powerpc/kernel/traps.c:altivec_assist_exception",
        "arch/powerpc/kernel/traps.c:facility_unavailable_exception",
        "arch/powerpc/kernel/traps.c:facility_unavailable_exception",
        "arch/powerpc/kernel/traps.c:vsx_unavailable_exception",
        "arch/powerpc/kernel/traps.c:altivec_unavailable_exception",
        "arch/powerpc/kernel/traps.c:kernel_fp_unavailable_exception",
        "arch/powerpc/kernel/traps.c:program_check_exception",
        "arch/powerpc/kernel/traps.c:SMIException",
        "arch/powerpc/kernel/traps.c:machine_check_exception",
        "arch/powerpc/kernel/traps.c:machine_check_exception",
        "arch/powerpc/kernel/traps.c:system_reset_exception",
        "arch/powerpc/kernel/traps.c:_exception",
        "arch/powerpc/kernel/traps.c:_exception_pkey",
        "arch/powerpc/mm/fault.c:bad_page_fault",
        "arch/powerpc/platforms/powernv/opal.c:opal_machine_check",
        "arch/powerpc/platforms/pseries/ras.c:pSeries_machine_check_exception",
        "arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_bad_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282346464,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void die(struct pt_regs * regs, const char * str)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271346576,
      "name": "die",
      "external": true,
      "loc": "arch/riscv/kernel/traps.c:29",
      "file": "arch/riscv/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:do_trap_break",
        "arch/riscv/mm/fault.c:do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271346576,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064608,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:403",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064608,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578997360,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:403",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578997360,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064192,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:403",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064192,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068256,
      "name": "die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:403",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_device_not_available",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_double_fault",
        "arch/x86/kernel/traps.c:handle_stack_overflow",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068256,
      "name": "die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int err</code> ➡️ <code>int err</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int err</code> ➡️ <code>int err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long int err</code>
</li>
<li>
<b>Param reordered. </b>
<code>str, regs, err</code> ➡️ <code>regs, str</code>
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

# Function: <code>fixup_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287456,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:17",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287456,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287504,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:99",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287504,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int fixup_exception(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302896,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:99",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302896,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int fixup_exception(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300624,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:101",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300624,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fixup_exception(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322032,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:173",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322032,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int fixup_exception(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579332800,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:173",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332800,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359088,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:200",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359088,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373680,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:202",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373680,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377968,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:202",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377968,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406656,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:141",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406656,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407232,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:158",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407232,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410464,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:158",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410464,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473216,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:158",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473216,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:152",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:gp_try_fixup_and_notify",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593854403,
      "name": "fixup_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579550192,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:205",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:gp_try_fixup_and_notify",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595969188,
      "name": "fixup_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579656672,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:233",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:gp_try_fixup_and_notify",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596486830,
      "name": "fixup_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579670864,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 899
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:233",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:gp_try_fixup_and_notify",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597383452,
      "name": "fixup_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579704752,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 899
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
int fixup_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490339456,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/arm64/mm/extable.c:9",
      "file": "arch/arm64/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler",
        "arch/arm64/mm/fault.c:__do_kernel_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490339456,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int fixup_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224478300,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/arm/mm/extable.c:8",
      "file": "arch/arm/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/fault.c:do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224478300,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fixup_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271359730,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/riscv/mm/extable.c:14",
      "file": "arch/riscv/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/fault.c:do_page_fault",
        "arch/riscv/mm/fault.c:do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271359730,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373872,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:202",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373872,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304064,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:202",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304064,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373792,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:202",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373792,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382272,
      "name": "fixup_exception",
      "external": true,
      "loc": "arch/x86/mm/extable.c:202",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382272,
      "name": "fixup_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int trapnr</code>
</li>
</ul>
</details>
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
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int fault_addr</code>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int fixup_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
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

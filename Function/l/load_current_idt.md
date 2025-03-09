# Function: <code>load_current_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579108152,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:495",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263947,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:495",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579111542,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:495",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263323,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:495",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579110083,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:495",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276923,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:495",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579101766,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:602",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273451,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:602",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tracepoint.c:switch_idt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579113267,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_reset",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203399,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579119619,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215399,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579125355,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239079,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579135001,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253678,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579136921,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255390,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579060208,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:168",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060208,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062272,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:158",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062272,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068992,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:158",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068992,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090240,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:166",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090240,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579119024,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:174",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579119024,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158528,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:174",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158528,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160688,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:174",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160688,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void load_current_idt()
```

```json
{
  "name": "load_current_idt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190000,
      "name": "load_current_idt",
      "external": true,
      "loc": "arch/x86/kernel/idt.c:177",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190000,
      "name": "load_current_idt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579137305,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254094,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579068063,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189342,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579136857,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255294,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_current_idt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579141977,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero",
        "arch/x86/kernel/cpu/common.c:debug_stack_set_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260862,
      "name": "load_current_idt",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:426",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void load_current_idt()
```
</details>
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

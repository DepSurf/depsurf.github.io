# Function: <code>native_safe_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579253353,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:47",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256288,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:47",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256288,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579252281,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:47",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255344,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:47",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255344,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265781,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101472,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101472,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579262464,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327104,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327104,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579280372,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:52",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893232,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893232,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579291748,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:55",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271440,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:55",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271440,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579316788,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:55",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589514288,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:55",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589514288,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579331946,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973424,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589973424,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336122,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200832,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590200832,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591216736,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591216736,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591711248,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591711248,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591658640,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:48",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658640,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592832320,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:48",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592832320,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594741760,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:48",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594741760,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596494048,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:48",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596494048,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596937264,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:pv_native_safe_halt"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_safe_halt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597862480,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:pv_native_safe_halt"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579332026,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589803120,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803120,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589524571,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266574,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069677,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
      ],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589526256,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579331946,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246528,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246528,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_safe_halt()
```

```json
{
  "name": "native_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579340231,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297680,
      "name": "native_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590297680,
      "name": "native_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void native_safe_halt()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void native_safe_halt()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_safe_halt()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_safe_halt()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_safe_halt()
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

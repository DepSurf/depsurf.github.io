# Function: <code>arch_safe_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void arch_safe_halt()
```

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579078105,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253549,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583745343,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:115",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745343,
      "name": "arch_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void arch_safe_halt()
```

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579074139,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:105",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252557,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:105",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584069785,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:105",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069785,
      "name": "arch_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void arch_safe_halt()
```

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588100763,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:96",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266045,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:96",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584212333,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:96",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212333,
      "name": "arch_safe_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588326315,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:96",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262686,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:96",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584282387,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:96",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588892443,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:92",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279919,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:92",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584684067,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:92",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589270715,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:92",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291037,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:92",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584910195,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:92",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589513341,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:154",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316077,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:154",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585014083,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:154",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589972459,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:154",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331323,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:154",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585218771,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:154",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590199867,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335499,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585355203,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591215915,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365743,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586061923,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591711029,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579364767,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586185052,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591658421,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579369215,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586060920,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592832069,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579430207,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586553762,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579175731,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579495672,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587811370,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579230243,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579591616,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589153393,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596945264,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604160,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589441023,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597872736,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:173",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579633888,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:173",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589748991,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:173",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589802155,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331403,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585156531,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589524571,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:101",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264072,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:101",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585070828,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:101",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_idle_do_entry"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590245563,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331323,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585306787,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
  "name": "arch_safe_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590296603,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:default_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339867,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585412931,
      "name": "arch_safe_halt",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:142",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead",
        "drivers/acpi/processor_idle.c:acpi_safe_halt"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void arch_safe_halt()
```
</details>
</li>
</ul>

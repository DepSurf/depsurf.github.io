# Function: <code>mwait_idle_with_hints</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579173071,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:98",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536172,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:98",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/idle/intel_idle.c:intel_idle_freeze"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579173439,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:98",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856873,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:98",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588101342,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:98",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995929,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:98",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588326974,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:99",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044089,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:99",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588893102,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:100",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308409,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:100",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589271310,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:100",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584528472,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:100",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589514158,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:100",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584625624,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:100",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589973262,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824089,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590200670,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959833,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
```

```json
{
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579273856,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:109",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ]
    },
    {
      "addr": 18446744071585654944,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:109",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273856,
      "name": "mwait_idle_with_hints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071585654944,
      "name": "mwait_idle_with_hints.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
```

```json
{
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281184,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ]
    },
    {
      "addr": 18446744071585781152,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281184,
      "name": "mwait_idle_with_hints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071585781152,
      "name": "mwait_idle_with_hints.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
```

```json
{
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579283936,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ]
    },
    {
      "addr": 18446744071585661728,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283936,
      "name": "mwait_idle_with_hints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071585661728,
      "name": "mwait_idle_with_hints.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
```

```json
{
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579327744,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ]
    },
    {
      "addr": 18446744071586140304,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327744,
      "name": "mwait_idle_with_hints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071586140304,
      "name": "mwait_idle_with_hints.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
```

```json
{
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387728,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ]
    },
    {
      "addr": 18446744071587371456,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_irq",
        "drivers/idle/intel_idle.c:intel_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387728,
      "name": "mwait_idle_with_hints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071587371456,
      "name": "mwait_idle_with_hints.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
```

```json
{
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579466208,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:108",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ]
    },
    {
      "addr": 18446744071588619952,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:108",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle_xstate",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_irq",
        "drivers/idle/intel_idle.c:intel_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466208,
      "name": "mwait_idle_with_hints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071588619952,
      "name": "mwait_idle_with_hints.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596945603,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:108",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596946936,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:108",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle_xstate",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_irq",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597873064,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:117",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597874440,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:117",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle_xstate",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_irq",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589802958,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909993,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589525374,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584815897,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590246366,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911417,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
  "name": "mwait_idle_with_hints",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590297518,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017497,
      "name": "mwait_idle_with_hints",
      "external": false,
      "loc": "arch/x86/include/asm/mwait.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
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
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx)
```
</details>
</li>
</ul>

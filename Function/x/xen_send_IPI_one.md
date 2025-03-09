# Function: <code>xen_send_IPI_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864688,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1197",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864688,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584195216,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1208",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195216,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376704,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1207",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376704,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584458144,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1199",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458144,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584868832,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1199",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868832,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1197",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585101330,
      "name": "xen_send_IPI_one.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585099792,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1197",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212108,
      "name": "xen_send_IPI_one.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585210528,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1198",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424631,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585422832,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1198",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565108,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585563504,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1213",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286294,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071586284800,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1595",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591448551,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071586405024,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1632",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591390252,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586288256,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1638",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592433907,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586803824,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1638",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594302011,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588085776,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589468048,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1640",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589468048,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589767968,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1634",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589767968,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590104560,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1624",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104560,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498226120,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1198",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498226120,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1202",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585327076,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585325216,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1198",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585515508,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585513904,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```

```json
{
  "name": "xen_send_IPI_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_send_IPI_one",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1198",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_self",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_reschedule",
        "arch/x86/xen/spinlock.c:xen_qlock_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623524,
      "name": "xen_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585621920,
      "name": "xen_send_IPI_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

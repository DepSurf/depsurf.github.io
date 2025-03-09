# Function: <code>shpchp_handle_power_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339296,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339296,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434496,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434496,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631891,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071584629328,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769587,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071584767024,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461053,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071585458448,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591415182,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071585605760,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591357545,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071585484144,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592385702,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071585950848,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594249603,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071587154960,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596211125,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588363168,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596736273,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588639248,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597644857,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588939616,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497033032,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497033032,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275690160,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275690160,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718403,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071584715840,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649171,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071584646608,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719747,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071584717184,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_power_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_power_fault",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:141",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827331,
      "name": "shpchp_handle_power_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071584824768,
      "name": "shpchp_handle_power_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```
</details>
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller * ctrl)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

# Function: <code>shpchp_handle_presence_change</code>

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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339024,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584339024,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434240,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584434240,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584631727,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584629200,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584769423,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584766896,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071585460889,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071585458320,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071591415018,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071585605632,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071591357381,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071585484016,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071592385515,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071585950704,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071594249405,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071587154816,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071596211104,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588362864,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071596736252,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588638944,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071597644836,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588939312,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497032744,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446603336497032744,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275689910,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446743936275689910,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584718239,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584715712,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584649007,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584646480,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584719583,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584717056,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_presence_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_presence_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:106",
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
      "addr": 18446744071584827167,
      "name": "shpchp_handle_presence_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584824640,
      "name": "shpchp_handle_presence_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller * ctrl)
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

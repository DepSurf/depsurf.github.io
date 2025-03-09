# Function: <code>shpchp_handle_switch_change</code>

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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338576,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584338576,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584433808,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584433808,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584631467,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071584629024,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584769163,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071584766720,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071585460629,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585458144,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071591414758,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585605456,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071591357121,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071585483840,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071592385210,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071585950512,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071594249089,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071587154624,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071596211062,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588362368,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071596736210,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588638448,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071597644794,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588938816,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497032312,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446603336497032312,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275689566,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446743936275689566,
      "name": "shpchp_handle_switch_change",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584717979,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071584715536,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584648747,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071584646304,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584719323,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071584716880,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_switch_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_switch_change",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:68",
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
      "addr": 18446744071584826907,
      "name": "shpchp_handle_switch_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071584824464,
      "name": "shpchp_handle_switch_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller * ctrl)
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

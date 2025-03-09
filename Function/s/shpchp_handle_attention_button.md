# Function: <code>shpchp_handle_attention_button</code>

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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338352,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584338352,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584433584,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584433584,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584631397,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584628864,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584769093,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584766560,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071585460559,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071585457984,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071591414688,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071585605296,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071591357051,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071585483680,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071592385119,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585950320,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071594248997,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071587154432,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071596211041,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588362096,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071596736189,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588638176,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071597644773,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588938544,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497032064,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446603336497032064,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275689354,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446743936275689354,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584717909,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584715376,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584648677,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584646144,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584719253,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584716720,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```

```json
{
  "name": "shpchp_handle_attention_button",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_handle_attention_button",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:45",
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
      "addr": 18446744071584826837,
      "name": "shpchp_handle_attention_button.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584824304,
      "name": "shpchp_handle_attention_button",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller * ctrl)
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

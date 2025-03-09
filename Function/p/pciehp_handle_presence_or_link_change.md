# Function: <code>pciehp_handle_presence_or_link_change</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418576,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:216",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418576,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1022
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:222",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615768,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
    },
    {
      "addr": 18446744071584614640,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754075,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071584752576,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445428,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585444000,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:225",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411594,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585593392,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:225",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591353858,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585471792,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:225",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592381405,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585938096,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:225",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594245255,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071587140960,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588344688,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:225",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588344688,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588620832,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:226",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588620832,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588921008,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:226",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921008,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497016296,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497016296,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275675902,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275675902,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702891,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071584701392,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633659,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071584632160,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704235,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071584702736,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```

```json
{
  "name": "pciehp_handle_presence_or_link_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_handle_presence_or_link_change",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:227",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584811878,
      "name": "pciehp_handle_presence_or_link_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071584810384,
      "name": "pciehp_handle_presence_or_link_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pciehp_handle_presence_or_link_change(struct controller * ctrl, u32 events)
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

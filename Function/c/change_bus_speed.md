# Function: <code>change_bus_speed</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584336048,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336048,
      "name": "change_bus_speed.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584431296,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431296,
      "name": "change_bus_speed.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584630568,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627344,
      "name": "change_bus_speed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584630532,
      "name": "change_bus_speed.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584768264,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765040,
      "name": "change_bus_speed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584768228,
      "name": "change_bus_speed.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585459479,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456160,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585459442,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591413608,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585603472,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071591413571,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591355987,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481888,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071591355950,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947904,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071592383738,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151872,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071594247576,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358320,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071596210762,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634416,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071596735914,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934736,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071597644498,
      "name": "change_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497029792,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497029792,
      "name": "change_bus_speed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275687414,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275687414,
      "name": "change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584717080,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713856,
      "name": "change_bus_speed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584717044,
      "name": "change_bus_speed.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584647848,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644624,
      "name": "change_bus_speed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584647812,
      "name": "change_bus_speed.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584718424,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715200,
      "name": "change_bus_speed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584718388,
      "name": "change_bus_speed.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584826008,
      "name": "change_bus_speed",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:178",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added",
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822784,
      "name": "change_bus_speed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584825972,
      "name": "change_bus_speed.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int change_bus_speed(struct controller * ctrl, struct slot * p_slot, enum pci_bus_speed speed)
```
</details>
</li>
</ul>

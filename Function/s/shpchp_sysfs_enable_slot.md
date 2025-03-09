# Function: <code>shpchp_sysfs_enable_slot</code>

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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339840,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:648",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot",
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339840,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435024,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot",
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435024,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632137,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584629632,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769833,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584767328,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:636",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461300,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585458752,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:635",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591415429,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585606064,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:635",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591357792,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585484464,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:635",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592385970,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071585951184,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:635",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594249881,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071587155280,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588363776,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:635",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot",
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588363776,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588639856,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:635",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot",
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588639856,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588940256,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:635",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot",
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940256,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497033576,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497033576,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275690664,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275690664,
      "name": "shpchp_sysfs_enable_slot",
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718649,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584716144,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649417,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584646912,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719993,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584717488,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_enable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_enable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:637",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827577,
      "name": "shpchp_sysfs_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584825072,
      "name": "shpchp_sysfs_enable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
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
int shpchp_sysfs_enable_slot(struct slot * p_slot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpchp_sysfs_enable_slot(struct slot * p_slot)
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

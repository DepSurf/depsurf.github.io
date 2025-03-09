# Function: <code>shpchp_sysfs_disable_slot</code>

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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584340112,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:683",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot",
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340112,
      "name": "shpchp_sysfs_disable_slot",
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435280,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot",
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435280,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632277,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584629760,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769973,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584767456,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:672",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461440,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585458880,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:671",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591415569,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585606192,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:671",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591357932,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585484592,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:671",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592386110,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585951312,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:671",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594249999,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071587155408,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588364032,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:671",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot",
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364032,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588640112,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:671",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot",
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588640112,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588940512,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:671",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot",
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940512,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497033848,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497033848,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275690914,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275690914,
      "name": "shpchp_sysfs_disable_slot",
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718789,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584716272,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649557,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584647040,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720133,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584717616,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_sysfs_disable_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_sysfs_disable_slot",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:673",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827717,
      "name": "shpchp_sysfs_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584825200,
      "name": "shpchp_sysfs_disable_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
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
int shpchp_sysfs_disable_slot(struct slot * p_slot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpchp_sysfs_disable_slot(struct slot * p_slot)
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

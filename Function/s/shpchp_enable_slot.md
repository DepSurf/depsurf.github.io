# Function: <code>shpchp_enable_slot</code>

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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584337248,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:555",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584337248,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432496,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432496,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584628000,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071584631176,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765696,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071584768872,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:543",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456800,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071585460088,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:542",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604112,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071591414217,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:542",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482528,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071591356596,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:542",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949136,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071592384612,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:542",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153200,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071594248520,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:542",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588360368,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071596210992,
      "name": "shpchp_enable_slot.cold",
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:542",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636448,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071596736140,
      "name": "shpchp_enable_slot.cold",
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:542",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588936768,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071597644724,
      "name": "shpchp_enable_slot.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497030984,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497030984,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275688388,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275688388,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714512,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071584717688,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645280,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071584648456,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715856,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071584719032,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int shpchp_enable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:544",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823440,
      "name": "shpchp_enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071584826616,
      "name": "shpchp_enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int shpchp_enable_slot(struct slot * p_slot)
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
int shpchp_enable_slot(struct slot * p_slot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpchp_enable_slot(struct slot * p_slot)
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

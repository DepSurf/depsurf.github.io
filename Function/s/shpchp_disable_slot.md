# Function: <code>shpchp_disable_slot</code>

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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335360,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:612",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335360,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584430624,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584430624,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626896,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071584630253,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764592,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071584767949,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:600",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457568,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071585460430,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:599",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604880,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071591414559,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:599",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482992,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071591356773,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:599",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949616,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071592384806,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:599",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153696,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    },
    {
      "addr": 18446744071594248696,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:599",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361056,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
    },
    {
      "addr": 18446744071596211013,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:599",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588637136,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
    },
    {
      "addr": 18446744071596736161,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:599",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588937456,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
    },
    {
      "addr": 18446744071597644745,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497029136,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497029136,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275686898,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275686898,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713408,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071584716765,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644176,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071584647533,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714752,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071584718109,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int shpchp_disable_slot(struct slot * p_slot)
```

```json
{
  "name": "shpchp_disable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpchp_disable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:601",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_pushbutton_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822336,
      "name": "shpchp_disable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071584825693,
      "name": "shpchp_disable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int shpchp_disable_slot(struct slot * p_slot)
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
int shpchp_disable_slot(struct slot * p_slot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpchp_disable_slot(struct slot * p_slot)
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

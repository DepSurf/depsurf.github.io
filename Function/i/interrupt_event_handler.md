# Function: <code>interrupt_event_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583364240,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:362",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364240,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583662928,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/pcie/pcie-dpc.c:37",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583677488,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:362",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662928,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071583677488,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800320,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/pcie/pcie-dpc.c:39",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583815616,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:347",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800320,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071583815616,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843760,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/pcie/pcie-dpc.c:60",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583858592,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:347",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843760,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071583858592,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107200,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/pcie/pcie-dpc.c:108",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584122176,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:348",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107200,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071584122176,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322688,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:334",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584334544,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:530",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322688,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    },
    {
      "addr": 18446744071584334544,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584429840,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584429840,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626448,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584629881,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764144,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584767577,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:518",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455680,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071585459351,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:517",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602992,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071591413480,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:517",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481408,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071591355859,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:517",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948000,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071592383837,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:517",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151984,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071594247677,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:517",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358528,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596210783,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:517",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634624,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596735935,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:517",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934944,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071597644519,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497028344,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497028344,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275686226,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275686226,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712960,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584716393,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643728,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584647161,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714304,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584717737,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void interrupt_event_handler(struct work_struct * work)
```

```json
{
  "name": "interrupt_event_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "interrupt_event_handler",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:519",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821888,
      "name": "interrupt_event_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071584825321,
      "name": "interrupt_event_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
void interrupt_event_handler(struct work_struct * work)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void interrupt_event_handler(struct work_struct * work)
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

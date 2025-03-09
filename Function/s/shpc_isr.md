# Function: <code>shpc_isr</code>

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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342512,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342512,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584437696,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437696,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634416,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071584637193,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772112,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071584774889,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585463584,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071585466297,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608128,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071591416035,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:767",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486560,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071591358390,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:767",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585953248,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    },
    {
      "addr": 18446744071592386676,
      "name": "shpc_isr.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:767",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157520,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071594250545,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:750",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366656,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 799
    },
    {
      "addr": 18446744071596211220,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:750",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642656,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    },
    {
      "addr": 18446744071596736368,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:750",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588943056,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    },
    {
      "addr": 18446744071597644952,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497039168,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497039168,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275693292,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275693292,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720928,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071584723705,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584651696,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071584654473,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722272,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071584725049,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```

```json
{
  "name": "shpc_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:772",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584829856,
      "name": "shpc_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071584832617,
      "name": "shpc_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
irqreturn_t shpc_isr(int irq, void * dev_id)
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
irqreturn_t shpc_isr(int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
irqreturn_t shpc_isr(int irq, void * dev_id)
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

# Function: <code>pciehp_isr</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583819936,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:561",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819936,
      "name": "pciehp_isr.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583862912,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:561",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862912,
      "name": "pciehp_isr.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126528,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:558",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126528,
      "name": "pciehp_isr.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584327264,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:538",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327264,
      "name": "pciehp_isr.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421856,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:513",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421856,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:515",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618304,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071584623987,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:527",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756288,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071584761683,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:563",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447376,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    },
    {
      "addr": 18446744071585452982,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:566",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595680,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    },
    {
      "addr": 18446744071591412136,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:592",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474080,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    },
    {
      "addr": 18446744071591354400,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:592",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940336,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    },
    {
      "addr": 18446744071592381967,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:594",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143616,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071594245816,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:594",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348000,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071596210384,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:588",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624256,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071596735536,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:589",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924432,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071597644120,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497020120,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:527",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497020120,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275678918,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:527",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275678918,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:527",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705104,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071584710499,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:527",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635872,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071584641267,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:527",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706448,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071584711843,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_isr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_isr",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:527",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814032,
      "name": "pciehp_isr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071584819431,
      "name": "pciehp_isr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
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
irqreturn_t pciehp_isr(int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
irqreturn_t pciehp_isr(int irq, void * dev_id)
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

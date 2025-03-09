# Function: <code>pciehp_ist</code>

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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584424656,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:602",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424656,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:604",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621088,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071584624109,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:616",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758864,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071584761805,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:666",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585450096,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071585453098,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:669",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598400,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071591412337,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:695",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476720,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071591354596,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:697",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943008,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071592382204,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:699",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587146464,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071594246040,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:699",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588351248,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071596210426,
      "name": "pciehp_ist.cold",
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:693",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588627504,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
    },
    {
      "addr": 18446744071596735578,
      "name": "pciehp_ist.cold",
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:694",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927680,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
    },
    {
      "addr": 18446744071597644162,
      "name": "pciehp_ist.cold",
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497022888,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:616",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497022888,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275681346,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:616",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275681346,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:616",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707680,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071584710621,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:616",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638448,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071584641389,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:616",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709024,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071584711965,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```

```json
{
  "name": "pciehp_ist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pciehp_ist",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:616",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816608,
      "name": "pciehp_ist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071584819553,
      "name": "pciehp_ist.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
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
irqreturn_t pciehp_ist(int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
irqreturn_t pciehp_ist(int irq, void * dev_id)
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

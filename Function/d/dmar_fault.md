# Function: <code>dmar_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296784,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1593",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296784,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644592,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1602",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644592,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830640,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1603",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830640,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920368,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1612",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920368,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341696,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1615",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341696,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1615",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585591855,
      "name": "dmar_fault.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071585584320,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1646",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716111,
      "name": "dmar_fault.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071585708240,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1635",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943935,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071585936064,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1708",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087087,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071586079232,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1824",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835836,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586827552,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1861",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591477671,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586884080,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1930",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591418125,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071586763744,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1966",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592472158,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071587318736,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1968",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594342005,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071588634144,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590103456,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1957",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590103456,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 994
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590417040,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1980",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590417040,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590761136,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1998",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:enable_drhd_fault_handling",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590761136,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1708",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585848207,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071585840352,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1708",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707247,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071585699392,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1708",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037103,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071586029248,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
irqreturn_t dmar_fault(int irq, void * dev_id)
```

```json
{
  "name": "dmar_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dmar_fault",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1708",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:enable_drhd_fault_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145087,
      "name": "dmar_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071586137200,
      "name": "dmar_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
irqreturn_t dmar_fault(int irq, void * dev_id)
```
</details>
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

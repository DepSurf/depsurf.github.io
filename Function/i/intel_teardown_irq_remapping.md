# Function: <code>intel_teardown_irq_remapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336480,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:594",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336480,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584683600,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:594",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584683600,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584870160,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:594",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870160,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584965120,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:601",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584961472,
      "name": "intel_teardown_irq_remapping.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386416,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:602",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585382768,
      "name": "intel_teardown_irq_remapping.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585624944,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:602",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624944,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585752112,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:604",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752112,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585983808,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:629",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585983808,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586130816,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:629",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130816,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586885840,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:635",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885840,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586936112,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:633",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936112,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586817712,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:634",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817712,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587377184,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:641",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377184,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588687104,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:641",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687104,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590165888,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:641",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165888,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590480128,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:634",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590480128,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590830656,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:634",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add",
        "drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590830656,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891184,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:629",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891184,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585750960,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:629",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750960,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586080832,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:629",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586080832,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```

```json
{
  "name": "intel_teardown_irq_remapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586189120,
      "name": "intel_teardown_irq_remapping",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:629",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189120,
      "name": "intel_teardown_irq_remapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu * iommu)
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

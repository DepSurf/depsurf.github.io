# Function: <code>modify_irte_ga</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807824,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3778",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807824,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898416,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3918",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898416,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585318976,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3711",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318976,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557840,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3771",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557840,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585682400,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3836",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682400,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585909008,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3817",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909008,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586052208,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3872",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586052208,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586805072,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3288",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586805072,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586864320,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3379",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864320,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586740416,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2745",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586740416,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2813",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587295632,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
    },
    {
      "addr": 18446744071592468796,
      "name": "modify_irte_ga.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588609328,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2839",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588609328,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int modify_irte_ga(struct amd_iommu * iommu, u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590071552,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3008",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590071552,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int modify_irte_ga(struct amd_iommu * iommu, u16 devid, int index, struct irte_ga * irte)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590374752,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3054",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590374752,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590716723,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3124",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd/iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd/iommu.c:irte_ga_activate"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585813184,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3872",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813184,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672368,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3872",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672368,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586002224,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3872",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002224,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```

```json
{
  "name": "modify_irte_ga",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586110512,
      "name": "modify_irte_ga",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3872",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode",
        "drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode",
        "drivers/iommu/amd_iommu.c:irte_ga_deactivate",
        "drivers/iommu/amd_iommu.c:irte_ga_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586110512,
      "name": "modify_irte_ga",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu * iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>devid, index, irte, data</code> ➡️ <code>iommu, devid, index, irte, data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct amd_ir_data * data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int modify_irte_ga(struct amd_iommu * iommu, u16 devid, int index, struct irte_ga * irte)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga * irte, struct amd_ir_data * data)
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

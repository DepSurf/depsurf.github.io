# Function: <code>modify_irte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291104,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3661",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irq_remapping_deactivate",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity"
      ]
    },
    {
      "addr": 18446744071584337312,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:154",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291104,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071584337312,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int modify_irte(u16 devid, int index, union irte irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584622048,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3675",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_deactivate"
      ]
    },
    {
      "addr": 18446744071584684400,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:154",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584622048,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071584684400,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807520,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3813",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071584870960,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:154",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807520,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071584870960,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898032,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3953",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071584959856,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:154",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898032,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071584959856,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585318592,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3746",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071585381120,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:155",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318592,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071585381120,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585558704,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3806",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071585625104,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:155",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585558704,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071585625104,
      "name": "modify_irte.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585683296,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3871",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071585752272,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:157",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683296,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071585752272,
      "name": "modify_irte.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585909920,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3852",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 0,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:157",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909920,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071585983968,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    },
    {
      "addr": 18446744071585988288,
      "name": "modify_irte.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586053232,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3907",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071586130976,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:157",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053232,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071586130976,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586804448,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3332",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071586887104,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:157",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586804448,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071586887104,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586863648,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3423",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071586937248,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:157",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863648,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071586937248,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586740032,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2789",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071586818832,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:158",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586740032,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071586818832,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2857",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071587378768,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:158",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294896,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071592468776,
      "name": "modify_irte.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587378768,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588608928,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2883",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071588688048,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:158",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608928,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071588688048,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590069968,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3047",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071590166848,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:159",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069968,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071590166848,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590376160,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3087",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071590481088,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:159",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590376160,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071590481088,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590717136,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3138",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:irte_set_affinity",
        "drivers/iommu/amd/iommu.c:irte_deactivate",
        "drivers/iommu/amd/iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071590835280,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:159",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590717136,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071590835280,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585814208,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3907",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071585891344,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:157",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814208,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071585891344,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585673392,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3907",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071585751120,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:157",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673392,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071585751120,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586003248,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3907",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071586080992,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:157",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586003248,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071586080992,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```

```json
{
  "name": "modify_irte",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586111536,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3907",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:irte_set_affinity",
        "drivers/iommu/amd_iommu.c:irte_deactivate",
        "drivers/iommu/amd_iommu.c:irte_activate"
      ]
    },
    {
      "addr": 18446744071586189280,
      "name": "modify_irte",
      "external": false,
      "loc": "drivers/iommu/intel_irq_remapping.c:157",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_deactivate",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_vcpu_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111536,
      "name": "modify_irte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071586189280,
      "name": "modify_irte.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>union irte irte</code> ➡️ <code>union irte * irte</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
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
int modify_irte(u16 devid, int index, union irte * irte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int modify_irte(u16 devid, int index, union irte * irte)
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

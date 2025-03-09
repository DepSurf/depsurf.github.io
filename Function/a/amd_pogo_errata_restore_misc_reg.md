# Function: <code>amd_pogo_errata_restore_misc_reg</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584337750,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:244",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584432998,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584628448,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584766144,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455840,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071585459398,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585603152,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071591413527,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481568,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071591355906,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948176,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071592383904,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587152160,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071594247744,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358768,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596210803,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
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
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634864,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596735955,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
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
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588935184,
      "name": "amd_pogo_errata_restore_misc_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071597644539,
      "name": "amd_pogo_errata_restore_misc_reg.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497031448,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275688738,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584714960,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584645728,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584716304,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_pogo_errata_restore_misc_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584823888,
      "name": "amd_pogo_errata_restore_misc_reg",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp.h:246",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot * p_slot)
```
</details>
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

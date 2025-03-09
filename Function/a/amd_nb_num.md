# Function: <code>amd_nb_num</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_nb_num",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579251379,
      "name": "amd_nb_num",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_num",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:69",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_num",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:69",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_nb_num",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595215855,
      "name": "amd_nb_num",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:77",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_num",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:77",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_num",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:77",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262512,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:63",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262512,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259328,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:63",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259328,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276128,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:67",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276128,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287472,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:73",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287472,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311424,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:93",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311424,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326592,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:94",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326592,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579330640,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:100",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330640,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359984,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:103",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359984,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359184,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:103",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359184,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363584,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:103",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363584,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424144,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:116",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424144,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579492624,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:116",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492624,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587472,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:129",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587472,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599968,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:137",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599968,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629728,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:153",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629728,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326544,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:100",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326544,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260992,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:100",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260992,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326464,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:100",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326464,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
```

```json
{
  "name": "amd_nb_num",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334752,
      "name": "amd_nb_num",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:100",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334752,
      "name": "amd_nb_num",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
u16 amd_nb_num()
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
u16 amd_nb_num()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u16 amd_nb_num()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u16 amd_nb_num()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u16 amd_nb_num()
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

# Function: <code>get_amd_iommu</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584916005,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:2745",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915824,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585336341,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:2942",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336160,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585577669,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:2943",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577488,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585702421,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:2979",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702240,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585930181,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3053",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585930000,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586073317,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3084",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586073136,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586818949,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3054",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818768,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586877125,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3269",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586876944,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586753557,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3217",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757552,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587306885,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3257",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312032,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588621269,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3267",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626736,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590084853,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3568",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590092272,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590396997,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3648",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590405008,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590740005,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3670",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:init_one_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590748576,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585834437,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3084",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834256,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585693109,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3084",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692928,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586023333,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3084",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586023152,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```

```json
{
  "name": "get_amd_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586131285,
      "name": "get_amd_iommu",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3084",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks"
      ],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131104,
      "name": "get_amd_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct amd_iommu * get_amd_iommu(unsigned int idx)
```
</details>
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
struct amd_iommu * get_amd_iommu(unsigned int idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct amd_iommu * get_amd_iommu(unsigned int idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct amd_iommu * get_amd_iommu(unsigned int idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct amd_iommu * get_amd_iommu(unsigned int idx)
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

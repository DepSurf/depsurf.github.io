# Function: <code>do_detach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584284602,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1913",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__detach_device"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584627786,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1793",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__detach_device"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584812890,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1886",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__detach_device"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584900282,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2133",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__detach_device"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585320842,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1904",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__detach_device"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585565537,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1915",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__detach_device"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585687776,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1996",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687776,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585915200,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1995",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585915200,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586059264,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2056",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059264,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802416,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1917",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802416,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586861584,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2008",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861584,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586748608,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1498",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586748608,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587302128,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1547",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587302128,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588614624,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1569",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588614624,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1671",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590077280,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    },
    {
      "addr": 18446744071596240689,
      "name": "do_detach.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1696",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590389008,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071596768791,
      "name": "do_detach.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1838",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590733952,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071597677280,
      "name": "do_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585820240,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2056",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585820240,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679424,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2056",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679424,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586009280,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2056",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009280,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void do_detach(struct iommu_dev_data * dev_data)
```

```json
{
  "name": "do_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586117568,
      "name": "do_detach",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2056",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117568,
      "name": "do_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void do_detach(struct iommu_dev_data * dev_data)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void do_detach(struct iommu_dev_data * dev_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void do_detach(struct iommu_dev_data * dev_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void do_detach(struct iommu_dev_data * dev_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void do_detach(struct iommu_dev_data * dev_data)
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

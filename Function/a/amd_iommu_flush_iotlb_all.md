# Function: <code>amd_iommu_flush_iotlb_all</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560448,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3174",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560448,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585687968,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3240",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687968,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585915392,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3221",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585915392,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586059744,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3256",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059744,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586803013,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2628",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802912,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586862197,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2719",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862096,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586752309,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2149",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750080,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587303968,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2210",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587303968,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588613232,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2227",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613232,
      "name": "amd_iommu_flush_iotlb_all",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590076480,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2376",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590076480,
      "name": "amd_iommu_flush_iotlb_all",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590386080,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2397",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590386080,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590736096,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2566",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590736096,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585820720,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3256",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585820720,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679904,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3256",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679904,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586009760,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3256",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009760,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```

```json
{
  "name": "amd_iommu_flush_iotlb_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118624,
      "name": "amd_iommu_flush_iotlb_all",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3256",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118624,
      "name": "amd_iommu_flush_iotlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
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
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain * domain)
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

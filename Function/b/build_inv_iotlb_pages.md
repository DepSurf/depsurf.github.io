# Function: <code>build_inv_iotlb_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584282067,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:745",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
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
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584624322,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:841",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
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
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584809453,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:911",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890560,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:969",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890560,
      "name": "build_inv_iotlb_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311760,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:910",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311760,
      "name": "build_inv_iotlb_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552448,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:916",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552448,
      "name": "build_inv_iotlb_pages",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585678000,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:931",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678000,
      "name": "build_inv_iotlb_pages",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904672,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:919",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904672,
      "name": "build_inv_iotlb_pages",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047664,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:926",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047664,
      "name": "build_inv_iotlb_pages",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586801839,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:870",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586861007,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:961",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586738812,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:910",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587292492,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:922",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588607800,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:944",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590070564,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1013",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:device_flush_iotlb"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590383508,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1030",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:device_flush_iotlb"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size, ioasid_t pasid, bool gn)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590711968,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1149",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590711968,
      "name": "build_inv_iotlb_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808640,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:926",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808640,
      "name": "build_inv_iotlb_pages",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667824,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:926",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667824,
      "name": "build_inv_iotlb_pages",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997680,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:926",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997680,
      "name": "build_inv_iotlb_pages",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```

```json
{
  "name": "build_inv_iotlb_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586105776,
      "name": "build_inv_iotlb_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:926",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586105776,
      "name": "build_inv_iotlb_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size, ioasid_t pasid, bool gn)
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
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd * cmd, u16 devid, int qdep, u64 address, size_t size)
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

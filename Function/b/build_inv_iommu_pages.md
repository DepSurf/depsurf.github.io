# Function: <code>build_inv_iommu_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584281813,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:714",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
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
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584624065,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:810",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
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
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584809201,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:880",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890720,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:938",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890720,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311920,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:879",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311920,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552592,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:885",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552592,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585678144,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:900",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678144,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904800,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:888",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904800,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047792,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:895",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047792,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586810786,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:839",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795168,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586870317,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:930",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:__domain_flush_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853728,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586745717,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:896",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587301895,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:908",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_dte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288688,
      "name": "build_inv_iommu_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588604609,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:930",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590065047,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:999",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590379120,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1016",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590379120,
      "name": "build_inv_iommu_pages.constprop.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, ioasid_t pasid, bool gn)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590720416,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1129",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590720416,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808768,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:895",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808768,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667952,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:895",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667952,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997808,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:895",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997808,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```

```json
{
  "name": "build_inv_iommu_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586105904,
      "name": "build_inv_iommu_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:895",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586105904,
      "name": "build_inv_iommu_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, ioasid_t pasid, bool gn)
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
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void build_inv_iommu_pages(struct iommu_cmd * cmd, u64 address, size_t size, u16 domid, int pde)
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

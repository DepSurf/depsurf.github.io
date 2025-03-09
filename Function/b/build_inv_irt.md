# Function: <code>build_inv_irt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584275238,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:836",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_flush_irt"
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
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584618118,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:932",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_flush_irt"
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
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584806566,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1002",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_flush_irt"
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890832,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1060",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890832,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312032,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1001",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312032,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552704,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1007",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552704,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585678256,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1022",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678256,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904912,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1010",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904912,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047904,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1017",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047904,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586813687,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:961",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586869719,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1052",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586742929,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:984",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
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
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587298165,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:996",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588614464,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1018",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
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
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590077100,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1087",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590370384,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1104",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590370384,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590711760,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1193",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590711760,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808880,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1017",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808880,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668064,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1017",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668064,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997920,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1017",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997920,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```

```json
{
  "name": "build_inv_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586106016,
      "name": "build_inv_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1017",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106016,
      "name": "build_inv_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```
</details>
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
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void build_inv_irt(struct iommu_cmd * cmd, u16 devid)
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

# Function: <code>iommu_flush_irt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iommu_flush_irt(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275232,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:962",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275232,
      "name": "iommu_flush_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void iommu_flush_irt(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618112,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1058",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618112,
      "name": "iommu_flush_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void iommu_flush_irt(struct amd_iommu * iommu, u16 devid)
```

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584806560,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1147",
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
      "addr": 18446744071584806560,
      "name": "iommu_flush_irt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584899869,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1206",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585320429,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1147",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585557353,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1153",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585681897,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1168",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585908494,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1167",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586051694,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1174",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586813687,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1118",
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
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586869719,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1208",
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
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586742929,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1140",
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
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587298165,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1152",
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
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588614464,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1174",
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
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590077100,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1245",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590394535,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1262",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590733268,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1351",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585812670,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1174",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585671854,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1174",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586001710,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1174",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_irt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586109998,
      "name": "iommu_flush_irt",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1174",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void iommu_flush_irt(struct amd_iommu * iommu, u16 devid)
```
</details>
</li>
</ul>

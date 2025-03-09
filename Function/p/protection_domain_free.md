# Function: <code>protection_domain_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276448,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2814",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276448,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619312,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2800",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619312,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584801984,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2893",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801984,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584900691,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3039",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893568,
      "name": "protection_domain_free.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585321251,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2821",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315040,
      "name": "protection_domain_free.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585565955,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2832",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564656,
      "name": "protection_domain_free.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585690125,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2896",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585689888,
      "name": "protection_domain_free.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585917136,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2877",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917136,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586061472,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2911",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586061472,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586815280,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2311",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586815280,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586874464,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2403",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874464,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586746704,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1832",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586746704,
      "name": "protection_domain_free",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587303376,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1871",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free"
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
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588615024,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1887",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free"
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
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590077728,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1992",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free"
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
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590389540,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2017",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_free"
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590712352,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2065",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590712352,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822448,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2911",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822448,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681632,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2911",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681632,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586011488,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2911",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586011488,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void protection_domain_free(struct protection_domain * domain)
```

```json
{
  "name": "protection_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586105600,
      "name": "protection_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2911",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586105600,
      "name": "protection_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void protection_domain_free(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void protection_domain_free(struct protection_domain * domain)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void protection_domain_free(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void protection_domain_free(struct protection_domain * domain)
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
void protection_domain_free(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void protection_domain_free(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void protection_domain_free(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void protection_domain_free(struct protection_domain * domain)
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

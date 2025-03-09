# Function: <code>iova_rcache_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584614470,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:794",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584798380,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:794",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584887500,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:767",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585307724,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:927",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585548613,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:927",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585673013,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:936",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899712,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:935",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:free_iova_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899712,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042608,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:937",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:free_iova_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042608,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586791984,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:939",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:fq_ring_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586791984,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586975104,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:913",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586856928,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:950",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587418469,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:963",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588734725,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:814",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590219893,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:817",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590539573,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:823",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590893381,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:858",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_iova_fast"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498861672,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:937",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:free_iova_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498861672,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585803584,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:937",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:free_iova_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585803584,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662768,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:937",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:free_iova_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662768,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585992624,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:937",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:free_iova_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585992624,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```

```json
{
  "name": "iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586101424,
      "name": "iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:937",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:free_iova_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101424,
      "name": "iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool iova_rcache_insert(struct iova_domain * iovad, long unsigned int pfn, long unsigned int size)
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

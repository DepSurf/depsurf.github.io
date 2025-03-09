# Function: <code>iova_rcache_get</code>

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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584616230,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:850",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584799487,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:850",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584888687,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:822",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585309727,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:982",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585550613,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:982",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585675029,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:991",
      "file": "drivers/iommu/iova.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585901440,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:990",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901440,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044384,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:992",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044384,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793456,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:994",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793456,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586976371,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:968",
      "file": "drivers/iommu/iova.c",
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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586856242,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:1005",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587419748,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:1018",
      "file": "drivers/iommu/iova.c",
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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588733945,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:869",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590219145,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:872",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590538535,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:878",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
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
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590895146,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:913",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:alloc_iova_fast"
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498863808,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:992",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498863808,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805360,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:992",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805360,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664544,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:992",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664544,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994400,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:992",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994400,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```

```json
{
  "name": "iova_rcache_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586099184,
      "name": "iova_rcache_get",
      "external": false,
      "loc": "drivers/iommu/iova.c:992",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586099184,
      "name": "iova_rcache_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
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
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain * iovad, long unsigned int size, long unsigned int limit_pfn)
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

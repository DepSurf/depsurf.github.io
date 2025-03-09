# Function: <code>__iova_rcache_insert</code>

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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584614553,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:745",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584798453,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:745",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584887571,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:719",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585307795,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:879",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585548707,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:879",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585673107,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:888",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585899802,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:887",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_insert"
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586042698,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:889",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_insert"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool __iova_rcache_insert(struct iova_domain * iovad, struct iova_rcache * rcache, long unsigned int iova_pfn)
```

```json
{
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586791472,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:891",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:iova_rcache_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586791472,
      "name": "__iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
bool __iova_rcache_insert(struct iova_domain * iovad, struct iova_rcache * rcache, long unsigned int iova_pfn)
```

```json
{
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973856,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:865",
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
      "addr": 18446744071586973856,
      "name": "__iova_rcache_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586857045,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:902",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587418543,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:915",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588734784,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:766",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590219948,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:769",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590539628,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:775",
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590893443,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:820",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498861792,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:889",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_insert"
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585803674,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:889",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_insert"
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585662858,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:889",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_insert"
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585992714,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:889",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_insert"
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
  "name": "__iova_rcache_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586101514,
      "name": "__iova_rcache_insert",
      "external": false,
      "loc": "drivers/iommu/iova.c:889",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_insert"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool __iova_rcache_insert(struct iova_domain * iovad, struct iova_rcache * rcache, long unsigned int iova_pfn)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool __iova_rcache_insert(struct iova_domain * iovad, struct iova_rcache * rcache, long unsigned int iova_pfn)
```
</details>
</li>
</ul>

# Function: <code>dma_ops_domain_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584290158,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1751",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dma_ops_domain_free(struct dma_ops_domain * dom)
```

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584623888,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1646",
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
      "addr": 18446744071584623888,
      "name": "dma_ops_domain_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void dma_ops_domain_free(struct dma_ops_domain * dom)
```

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584805152,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1736",
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
      "addr": 18446744071584805152,
      "name": "dma_ops_domain_free",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584900727,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1969",
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
      "addr": 18446744071584894656,
      "name": "dma_ops_domain_free.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585321287,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1752",
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
      "addr": 18446744071585315888,
      "name": "dma_ops_domain_free.part.32",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585566048,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1755",
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
      "addr": 18446744071585564720,
      "name": "dma_ops_domain_free.part.35",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585690250,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1836",
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
      "addr": 18446744071585689952,
      "name": "dma_ops_domain_free.part.36",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585917489,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1826",
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
      "addr": 18446744071585917200,
      "name": "dma_ops_domain_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586061790,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1890",
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
      "addr": 18446744071586061536,
      "name": "dma_ops_domain_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585822766,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1890",
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
      "addr": 18446744071585822512,
      "name": "dma_ops_domain_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681950,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1890",
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
      "addr": 18446744071585681696,
      "name": "dma_ops_domain_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586011806,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1890",
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
      "addr": 18446744071586011552,
      "name": "dma_ops_domain_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_ops_domain_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117950,
      "name": "dma_ops_domain_free",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1890",
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
      "addr": 18446744071586109568,
      "name": "dma_ops_domain_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dma_ops_domain_free(struct dma_ops_domain * dom)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void dma_ops_domain_free(struct dma_ops_domain * dom)
```
</details>
</li>
</ul>

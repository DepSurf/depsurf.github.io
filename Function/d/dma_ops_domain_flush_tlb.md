# Function: <code>dma_ops_domain_flush_tlb</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void dma_ops_domain_flush_tlb(struct dma_ops_domain * dom)
```

```json
{
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584896336,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1846",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:queue_flush_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896336,
      "name": "dma_ops_domain_flush_tlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585317542,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1733",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585560517,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1736",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585688037,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1817",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585915461,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1807",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586059861,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1867",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585820837,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1867",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585680021,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1867",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586009877,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1867",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
  "name": "dma_ops_domain_flush_tlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586118741,
      "name": "dma_ops_domain_flush_tlb",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1867",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void dma_ops_domain_flush_tlb(struct dma_ops_domain * dom)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void dma_ops_domain_flush_tlb(struct dma_ops_domain * dom)
```
</details>
</li>
</ul>

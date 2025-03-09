# Function: <code>iommu_dma_alloc_remap</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_dma_alloc_remap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588725648,
      "name": "iommu_dma_alloc_remap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:845",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
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
  "name": "iommu_dma_alloc_remap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590210164,
      "name": "iommu_dma_alloc_remap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:853",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
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
  "name": "iommu_dma_alloc_remap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590531652,
      "name": "iommu_dma_alloc_remap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:894",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
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
  "name": "iommu_dma_alloc_remap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590887124,
      "name": "iommu_dma_alloc_remap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1013",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
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
void * iommu_dma_alloc_remap(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_alloc_remap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498847320,
      "name": "iommu_dma_alloc_remap",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:564",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498847320,
      "name": "iommu_dma_alloc_remap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1216
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * iommu_dma_alloc_remap(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```
</details>
</li>
</ul>

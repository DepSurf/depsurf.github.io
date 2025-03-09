# Function: <code>bounce_sync_single</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "bounce_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586109728,
      "name": "bounce_sync_single",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3802",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109728,
      "name": "bounce_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "bounce_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586852848,
      "name": "bounce_sync_single",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3672",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel/iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel/iommu.c:bounce_sync_single_for_device",
        "drivers/iommu/intel/iommu.c:bounce_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852848,
      "name": "bounce_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "bounce_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869968,
      "name": "bounce_sync_single",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3802",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869968,
      "name": "bounce_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "bounce_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585729872,
      "name": "bounce_sync_single",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3802",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585729872,
      "name": "bounce_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "bounce_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586059744,
      "name": "bounce_sync_single",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3802",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059744,
      "name": "bounce_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "bounce_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167792,
      "name": "bounce_sync_single",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3802",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167792,
      "name": "bounce_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
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
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bounce_sync_single(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
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

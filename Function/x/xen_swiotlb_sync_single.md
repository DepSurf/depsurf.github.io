# Function: <code>xen_swiotlb_sync_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "xen_swiotlb_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583911440,
      "name": "xen_swiotlb_sync_single",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:482",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583911440,
      "name": "xen_swiotlb_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "xen_swiotlb_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584243216,
      "name": "xen_swiotlb_sync_single",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:482",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243216,
      "name": "xen_swiotlb_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "xen_swiotlb_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584424736,
      "name": "xen_swiotlb_sync_single",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:489",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424736,
      "name": "xen_swiotlb_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "xen_swiotlb_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584507408,
      "name": "xen_swiotlb_sync_single",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:487",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507408,
      "name": "xen_swiotlb_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "xen_swiotlb_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584917440,
      "name": "xen_swiotlb_sync_single",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:487",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917440,
      "name": "xen_swiotlb_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "xen_swiotlb_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585148992,
      "name": "xen_swiotlb_sync_single",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:473",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585148992,
      "name": "xen_swiotlb_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```

```json
{
  "name": "xen_swiotlb_sync_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585259824,
      "name": "xen_swiotlb_sync_single",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:466",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259824,
      "name": "xen_swiotlb_sync_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    }
  ]
}
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void xen_swiotlb_sync_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target)
```
</details>
</li>
</ul>

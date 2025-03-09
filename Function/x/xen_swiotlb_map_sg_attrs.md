# Function: <code>xen_swiotlb_map_sg_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, struct dma_attrs * attrs)
```

```json
{
  "name": "xen_swiotlb_map_sg_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910736,
      "name": "xen_swiotlb_map_sg_attrs",
      "external": true,
      "loc": "drivers/xen/swiotlb-xen.c:539",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910736,
      "name": "xen_swiotlb_map_sg_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "xen_swiotlb_map_sg_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242496,
      "name": "xen_swiotlb_map_sg_attrs",
      "external": true,
      "loc": "drivers/xen/swiotlb-xen.c:539",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242496,
      "name": "xen_swiotlb_map_sg_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "xen_swiotlb_map_sg_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584424016,
      "name": "xen_swiotlb_map_sg_attrs",
      "external": true,
      "loc": "drivers/xen/swiotlb-xen.c:546",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424016,
      "name": "xen_swiotlb_map_sg_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "xen_swiotlb_map_sg_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584508576,
      "name": "xen_swiotlb_map_sg_attrs",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:561",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508576,
      "name": "xen_swiotlb_map_sg_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "xen_swiotlb_map_sg_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584918608,
      "name": "xen_swiotlb_map_sg_attrs",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:561",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918608,
      "name": "xen_swiotlb_map_sg_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "xen_swiotlb_map_sg_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585150112,
      "name": "xen_swiotlb_map_sg_attrs",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:547",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585150112,
      "name": "xen_swiotlb_map_sg_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "xen_swiotlb_map_sg_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585260896,
      "name": "xen_swiotlb_map_sg_attrs",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:535",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585260896,
      "name": "xen_swiotlb_map_sg_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs * attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
int xen_swiotlb_map_sg_attrs(struct device * hwdev, struct scatterlist * sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
</ul>

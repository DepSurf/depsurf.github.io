# Function: <code>swiotlb_find_slots</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int swiotlb_find_slots(struct device * dev, phys_addr_t orig_addr, size_t alloc_size)
```

```json
{
  "name": "swiotlb_find_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580279568,
      "name": "swiotlb_find_slots",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:461",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279568,
      "name": "swiotlb_find_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int swiotlb_find_slots(struct device * dev, phys_addr_t orig_addr, size_t alloc_size, unsigned int alloc_align_mask)
```

```json
{
  "name": "swiotlb_find_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451968,
      "name": "swiotlb_find_slots",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:490",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451968,
      "name": "swiotlb_find_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swiotlb_find_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580700457,
      "name": "swiotlb_find_slots",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:713",
      "file": "kernel/dma/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
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
  "name": "swiotlb_find_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580777609,
      "name": "swiotlb_find_slots",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:725",
      "file": "kernel/dma/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int swiotlb_find_slots(struct device * dev, phys_addr_t orig_addr, size_t alloc_size, unsigned int alloc_align_mask, struct io_tlb_pool * * retpool)
```

```json
{
  "name": "swiotlb_find_slots",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_find_slots",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:1127",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861808,
      "name": "swiotlb_find_slots",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071597410648,
      "name": "swiotlb_find_slots.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int swiotlb_find_slots(struct device * dev, phys_addr_t orig_addr, size_t alloc_size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int alloc_align_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int swiotlb_find_slots(struct device * dev, phys_addr_t orig_addr, size_t alloc_size, unsigned int alloc_align_mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int swiotlb_find_slots(struct device * dev, phys_addr_t orig_addr, size_t alloc_size, unsigned int alloc_align_mask, struct io_tlb_pool * * retpool)
```
</details>
</li>
</ul>

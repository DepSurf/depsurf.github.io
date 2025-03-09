# Function: <code>unmap_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "unmap_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583115392,
      "name": "unmap_single",
      "external": false,
      "loc": "lib/swiotlb.c:784",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115392,
      "name": "unmap_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "unmap_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583409584,
      "name": "unmap_single",
      "external": false,
      "loc": "lib/swiotlb.c:784",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409584,
      "name": "unmap_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "unmap_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583535200,
      "name": "unmap_single",
      "external": false,
      "loc": "lib/swiotlb.c:839",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535200,
      "name": "unmap_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
  "name": "unmap_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583572945,
      "name": "unmap_single",
      "external": false,
      "loc": "lib/swiotlb.c:839",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/swiotlb.c:swiotlb_unmap_page"
      ],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583572928,
      "name": "unmap_single.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
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
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "unmap_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583818640,
      "name": "unmap_single",
      "external": false,
      "loc": "lib/swiotlb.c:884",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583818640,
      "name": "unmap_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "unmap_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951552,
      "name": "unmap_single",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:847",
      "file": "kernel/dma/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951552,
      "name": "unmap_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void unmap_single(struct device * hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
</ul>

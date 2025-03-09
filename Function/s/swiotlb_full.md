# Function: <code>swiotlb_full</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swiotlb_full",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583115274,
      "name": "swiotlb_full",
      "external": false,
      "loc": "lib/swiotlb.c:707",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/swiotlb.c:swiotlb_map_page",
        "lib/swiotlb.c:swiotlb_map_sg_attrs"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swiotlb_full",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583410689,
      "name": "swiotlb_full",
      "external": false,
      "loc": "lib/swiotlb.c:707",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/swiotlb.c:swiotlb_map_sg_attrs",
        "lib/swiotlb.c:swiotlb_map_page"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swiotlb_full(struct device * dev, size_t size, enum dma_data_direction dir, int do_panic)
```

```json
{
  "name": "swiotlb_full",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583534720,
      "name": "swiotlb_full",
      "external": false,
      "loc": "lib/swiotlb.c:758",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_map_sg_attrs",
        "lib/swiotlb.c:swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534720,
      "name": "swiotlb_full",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void swiotlb_full(struct device * dev, size_t size, enum dma_data_direction dir, int do_panic)
```

```json
{
  "name": "swiotlb_full",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583572432,
      "name": "swiotlb_full",
      "external": false,
      "loc": "lib/swiotlb.c:758",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583572432,
      "name": "swiotlb_full",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void swiotlb_full(struct device * dev, size_t size, enum dma_data_direction dir, int do_panic)
```

```json
{
  "name": "swiotlb_full",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583818064,
      "name": "swiotlb_full",
      "external": false,
      "loc": "lib/swiotlb.c:803",
      "file": "lib/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/swiotlb.c:swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583818064,
      "name": "swiotlb_full",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swiotlb_full(struct device * dev, size_t size, enum dma_data_direction dir, int do_panic)
```

```json
{
  "name": "swiotlb_full",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_full",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:767",
      "file": "kernel/dma/swiotlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948368,
      "name": "swiotlb_full",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071579953085,
      "name": "swiotlb_full.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void swiotlb_full(struct device * dev, size_t size, enum dma_data_direction dir, int do_panic)
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void swiotlb_full(struct device * dev, size_t size, enum dma_data_direction dir, int do_panic)
```
</details>
</li>
</ul>

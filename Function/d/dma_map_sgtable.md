# Function: <code>dma_map_sgtable</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_map_sgtable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587475277,
      "name": "dma_map_sgtable",
      "external": false,
      "loc": "include/linux/dma-mapping.h:319",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587485952,
      "name": "dma_map_sgtable",
      "external": false,
      "loc": "include/linux/dma-mapping.h:319",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_map_sgtable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587357069,
      "name": "dma_map_sgtable",
      "external": false,
      "loc": "include/linux/dma-mapping.h:362",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587367568,
      "name": "dma_map_sgtable",
      "external": false,
      "loc": "include/linux/dma-mapping.h:362",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int dma_map_sgtable(struct device * dev, struct sg_table * sgt, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_map_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580266832,
      "name": "dma_map_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:259",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266832,
      "name": "dma_map_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int dma_map_sgtable(struct device * dev, struct sg_table * sgt, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_map_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437216,
      "name": "dma_map_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:259",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437216,
      "name": "dma_map_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int dma_map_sgtable(struct device * dev, struct sg_table * sgt, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_map_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680560,
      "name": "dma_map_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:266",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf",
        "drivers/spi/spi.c:spi_map_buf_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680560,
      "name": "dma_map_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int dma_map_sgtable(struct device * dev, struct sg_table * sgt, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_map_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757072,
      "name": "dma_map_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:270",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf",
        "drivers/spi/spi.c:spi_map_buf_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757072,
      "name": "dma_map_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int dma_map_sgtable(struct device * dev, struct sg_table * sgt, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_map_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842192,
      "name": "dma_map_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:270",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf",
        "drivers/gpu/drm/drm_prime.c:drm_gem_map_dma_buf",
        "drivers/spi/spi.c:spi_map_buf_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842192,
      "name": "dma_map_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int dma_map_sgtable(struct device * dev, struct sg_table * sgt, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

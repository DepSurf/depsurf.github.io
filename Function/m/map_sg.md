# Function: <code>map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction dir, struct dma_attrs * attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584288704,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2555",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288704,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631184,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2445",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631184,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584815728,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2538",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815728,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584904960,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2699",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584904960,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585326032,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2480",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585326032,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2490",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567040,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071585576209,
      "name": "map_sg.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2566",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692064,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071585700946,
      "name": "map_sg.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2544",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585919280,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    },
    {
      "addr": 18446744071585927787,
      "name": "map_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2574",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586063568,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071586071182,
      "name": "map_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2574",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824544,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071585832302,
      "name": "map_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2574",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683728,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071585691342,
      "name": "map_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2574",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586013584,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071586021198,
      "name": "map_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_sg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2574",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586121536,
      "name": "map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071586129150,
      "name": "map_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dma_data_direction direction</code>
</li>
<li>
<b>Param removed. </b>
<code>enum dma_data_direction dir</code>
</li>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
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
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int map_sg(struct device * dev, struct scatterlist * sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs)
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

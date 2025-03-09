# Function: <code>iommu_get_dma_domain</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663792,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1453",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663792,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585891200,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1670",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891200,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586033888,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033888,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586773184,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2039",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap",
        "drivers/iommu/amd/iommu.c:attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773184,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586956832,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2249",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956832,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586838704,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2280",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586838704,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399840,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2301",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399840,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710448,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2062",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710448,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192560,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2100",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192560,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590514016,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2078",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590514016,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590869392,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2337",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590869392,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498835504,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map",
        "drivers/iommu/dma-iommu.c:__iommu_dma_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498835504,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231440940,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231440940,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292052448,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292052448,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794864,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794864,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585654048,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585654048,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585983904,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585983904,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```

```json
{
  "name": "iommu_get_dma_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586091792,
      "name": "iommu_get_dma_domain",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1726",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091792,
      "name": "iommu_get_dma_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iommu_domain * iommu_get_dma_domain(struct device * dev)
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

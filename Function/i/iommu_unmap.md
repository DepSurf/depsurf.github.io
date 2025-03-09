# Function: <code>iommu_unmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261968,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1367",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/iommu/iommu.c:default_iommu_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261968,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584603024,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1358",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584603024,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784688,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1509",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784688,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584873920,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1559",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873920,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585294539,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1620",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293760,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585535211,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1626",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534448,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585660327,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1702",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659568,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585886666,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1923",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885856,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028016,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028016,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769280,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2300",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp",
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769280,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950064,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2520",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp",
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950064,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586829504,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2551",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829504,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587389952,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2637",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389952,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701408,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2414",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701408,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182560,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2478",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182560,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590506832,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2490",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590506832,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590860176,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2754",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590860176,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498829504,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498829504,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231434380,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource",
        "arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:__iommu_remove_mapping",
        "arch/arm/mm/dma-mapping.c:__iommu_create_mapping",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231434380,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292040240,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292040240,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585788992,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788992,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585648176,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648176,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978032,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978032,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
```

```json
{
  "name": "iommu_unmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586085856,
      "name": "iommu_unmap",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085856,
      "name": "iommu_unmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
size_t iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size)
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

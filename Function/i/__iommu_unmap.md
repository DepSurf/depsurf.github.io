# Function: <code>__iommu_unmap</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, bool sync)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585293280,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1560",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293280,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, bool sync)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1566",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533984,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446744071585541306,
      "name": "__iommu_unmap.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, bool sync)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1642",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659120,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    },
    {
      "addr": 18446744071585665690,
      "name": "__iommu_unmap.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, bool sync)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1863",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885408,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071585892739,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027632,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071586035715,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2246",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768912,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071586776859,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2466",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949712,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071591482855,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2497",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829152,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071591426196,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2583",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389488,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071592483172,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2360",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588700896,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    },
    {
      "addr": 18446744071594352267,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2424",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182016,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071596244111,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2436",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590506288,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071596772490,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2700",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590859680,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071597681585,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498828984,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498828984,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231433880,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231433880,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292039568,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292039568,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788608,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071585796691,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647792,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071585655875,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977648,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071585985731,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
```

```json
{
  "name": "__iommu_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_unmap",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1919",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_unmap_fast",
        "drivers/iommu/iommu.c:iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085440,
      "name": "__iommu_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071586093642,
      "name": "__iommu_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, bool sync)
```
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_iotlb_gather * iotlb_gather</code>
</li>
<li>
<b>Param removed. </b>
<code>bool sync</code>
</li>
</ul>
</details>
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
size_t __iommu_unmap(struct iommu_domain * domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather * iotlb_gather)
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

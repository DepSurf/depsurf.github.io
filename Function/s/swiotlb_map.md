# Function: <code>swiotlb_map</code>

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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999072,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:626",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999072,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:655",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043384,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580042640,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092480,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580091664,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152560,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:663",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152560,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133840,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:678",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133840,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138800,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:630",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138800,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:677",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150710,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580282416,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:706",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593923510,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580454848,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:883",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595993675,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580701600,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:908",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596511922,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580778352,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
dma_addr_t swiotlb_map(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:1472",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597411133,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580866992,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491298392,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491298392,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": false,
      "loc": "include/linux/swiotlb.h:88",
      "file": "kernel/dma/direct.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284224928,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284224928,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271812360,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271812360,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061680,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580060864,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006528,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580005712,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052752,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580051936,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "swiotlb_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swiotlb_map",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:662",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103520,
      "name": "swiotlb_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580102688,
      "name": "swiotlb_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t paddr</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t * phys</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t * dma_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, phys, dma_addr, size, dir, attrs</code> ➡️ <code>dev, paddr, size, dir, attrs</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>dma_addr_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool swiotlb_map(struct device * dev, phys_addr_t * phys, dma_addr_t * dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

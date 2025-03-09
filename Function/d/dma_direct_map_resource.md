# Function: <code>dma_direct_map_resource</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036528,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036528,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086768,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086768,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:460",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149086,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580146672,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:417",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591310825,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580128656,
      "name": "dma_direct_map_resource",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:417",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591253156,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580132960,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:457",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150071,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071580276080,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:489",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922689,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071580447840,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:520",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595993060,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580692480,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:519",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596511320,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580769088,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:508",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410457,
      "name": "dma_direct_map_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580854976,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491289576,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491289576,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225295028,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225295028,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284215584,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284215584,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271805064,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271805064,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055504,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055504,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000816,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000816,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047040,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047040,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097792,
      "name": "dma_direct_map_resource",
      "external": true,
      "loc": "kernel/dma/direct.c:373",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097792,
      "name": "dma_direct_map_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
dma_addr_t dma_direct_map_resource(struct device * dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
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

# Function: <code>report_addr</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579994177,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:34",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_map_page"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036016,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071580037964,
      "name": "report_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086256,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071580088204,
      "name": "report_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491288824,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491288824,
      "name": "report_addr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225294548,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225294548,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284214640,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284214640,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271804548,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271804548,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054992,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071580057036,
      "name": "report_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000304,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071580002252,
      "name": "report_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046528,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071580048476,
      "name": "report_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```

```json
{
  "name": "report_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_addr",
      "external": false,
      "loc": "kernel/dma/direct.c:26",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_resource",
        "kernel/dma/direct.c:dma_direct_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097280,
      "name": "report_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071580099228,
      "name": "report_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void report_addr(struct device * dev, dma_addr_t dma_addr, size_t size)
```
</details>
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

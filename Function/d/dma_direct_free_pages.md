# Function: <code>dma_direct_free_pages</code>

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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995376,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:186",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995376,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037568,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037568,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087808,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087808,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148176,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:261",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148176,
      "name": "dma_direct_free_pages",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_addr, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127104,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:317",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127104,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void dma_direct_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_addr, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131424,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:317",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131424,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void dma_direct_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_addr, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:357",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150041,
      "name": "dma_direct_free_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580274912,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void dma_direct_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_addr, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:391",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922672,
      "name": "dma_direct_free_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580446496,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void dma_direct_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_addr, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580690928,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:391",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690928,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void dma_direct_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_addr, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767536,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:390",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767536,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void dma_direct_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_addr, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853280,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:379",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853280,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491290712,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491290712,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225296384,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225296384,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284216784,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284216784,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271805970,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271805970,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056624,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056624,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001856,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001856,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048080,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048080,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098832,
      "name": "dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:183",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098832,
      "name": "dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void dma_direct_free_pages(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param added. </b>
<code>enum dma_data_direction dir</code>
</li>
<li>
<b>Param removed. </b>
<code>void * cpu_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
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

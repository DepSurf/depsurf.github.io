# Function: <code>dma_coherent_ok</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579946508,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:54",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952275,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/swiotlb.c:694",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_alloc"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579994899,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:90",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580037006,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580087246,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146816,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:73",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146816,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580124661,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:68",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124112,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580129043,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:68",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128496,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580272353,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:68",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272688,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580443755,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:68",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444112,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580688000,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:68",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688432,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764597,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:69",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765040,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580850341,
      "name": "dma_coherent_ok",
      "external": true,
      "loc": "kernel/dma/direct.c:69",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850800,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491290004,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225295600,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284216080,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271805524,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055600,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055600,
      "name": "dma_coherent_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580001294,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580047518,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_coherent_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580098270,
      "name": "dma_coherent_ok",
      "external": false,
      "loc": "kernel/dma/direct.c:79",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
bool dma_coherent_ok(struct device * dev, phys_addr_t phys, size_t size)
```
</details>
</li>
</ul>

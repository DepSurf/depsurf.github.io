# Function: <code>__dma_direct_free_pages</code>

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
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995328,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995328,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580037662,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037520,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580087902,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087760,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580275053,
      "name": "__dma_direct_free_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:78",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580446618,
      "name": "__dma_direct_free_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:97",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580691050,
      "name": "__dma_direct_free_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:97",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580767658,
      "name": "__dma_direct_free_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:98",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853402,
      "name": "__dma_direct_free_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:98",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491290640,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:arch_dma_free",
        "kernel/dma/remap.c:arch_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491290640,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225296324,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225296344,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284216876,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284216704,
      "name": "__dma_direct_free_pages",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271805912,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271805912,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056717,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056592,
      "name": "__dma_direct_free_pages",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580001950,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001808,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048174,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048032,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
```

```json
{
  "name": "__dma_direct_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098926,
      "name": "__dma_direct_free_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:178",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098784,
      "name": "__dma_direct_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __dma_direct_free_pages(struct device * dev, size_t size, struct page * page)
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

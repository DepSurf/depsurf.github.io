# Function: <code>__dma_free_pages</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __dma_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_handle, enum dma_data_direction dir)
```

```json
{
  "name": "__dma_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580128133,
      "name": "__dma_free_pages",
      "external": false,
      "loc": "kernel/dma/mapping.c:509",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_free_pages"
      ],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125296,
      "name": "__dma_free_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void __dma_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_handle, enum dma_data_direction dir)
```

```json
{
  "name": "__dma_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271125,
      "name": "__dma_free_pages",
      "external": false,
      "loc": "kernel/dma/mapping.c:574",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_free_pages"
      ],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268368,
      "name": "__dma_free_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void __dma_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_handle, enum dma_data_direction dir)
```

```json
{
  "name": "__dma_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580442405,
      "name": "__dma_free_pages",
      "external": false,
      "loc": "kernel/dma/mapping.c:568",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_free_pages"
      ],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580439072,
      "name": "__dma_free_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void __dma_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_handle, enum dma_data_direction dir)
```

```json
{
  "name": "__dma_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580686757,
      "name": "__dma_free_pages",
      "external": false,
      "loc": "kernel/dma/mapping.c:585",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_free_pages"
      ],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682784,
      "name": "__dma_free_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void __dma_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_handle, enum dma_data_direction dir)
```

```json
{
  "name": "__dma_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580763173,
      "name": "__dma_free_pages",
      "external": false,
      "loc": "kernel/dma/mapping.c:589",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_free_pages"
      ],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759312,
      "name": "__dma_free_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void __dma_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_handle, enum dma_data_direction dir)
```

```json
{
  "name": "__dma_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580847941,
      "name": "__dma_free_pages",
      "external": false,
      "loc": "kernel/dma/mapping.c:589",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_free_pages"
      ],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_noncontiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844432,
      "name": "__dma_free_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void __dma_free_pages(struct device * dev, size_t size, struct page * page, dma_addr_t dma_handle, enum dma_data_direction dir)
```
</details>
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

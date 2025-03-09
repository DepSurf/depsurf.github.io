# Function: <code>__dma_alloc_from_pool</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct page * __dma_alloc_from_pool(struct device * dev, size_t size, struct gen_pool * pool, void * * cpu_addr, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153824,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:244",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153824,
      "name": "__dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
struct page * __dma_alloc_from_pool(struct device * dev, size_t size, struct gen_pool * pool, void * * cpu_addr, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134864,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:240",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134864,
      "name": "__dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580140139,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:240",
      "file": "kernel/dma/pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580283790,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:240",
      "file": "kernel/dma/pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
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
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580456366,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:240",
      "file": "kernel/dma/pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
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
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580703182,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:240",
      "file": "kernel/dma/pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct page * __dma_alloc_from_pool(struct device * dev, size_t size, struct gen_pool * pool, void * * cpu_addr, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779584,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:240",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779584,
      "name": "__dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct page * __dma_alloc_from_pool(struct device * dev, size_t size, struct gen_pool * pool, void * * cpu_addr, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "__dma_alloc_from_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868432,
      "name": "__dma_alloc_from_pool",
      "external": false,
      "loc": "kernel/dma/pool.c:240",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868432,
      "name": "__dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct page * __dma_alloc_from_pool(struct device * dev, size_t size, struct gen_pool * pool, void * * cpu_addr, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct page * __dma_alloc_from_pool(struct device * dev, size_t size, struct gen_pool * pool, void * * cpu_addr, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct page * __dma_alloc_from_pool(struct device * dev, size_t size, struct gen_pool * pool, void * * cpu_addr, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

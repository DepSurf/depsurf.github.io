# Function: <code>dma_alloc_from_pool</code>

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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580154256,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:269",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154256,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135296,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:265",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135296,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139968,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:265",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139968,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580283616,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:265",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283616,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580456288,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:265",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580456288,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703104,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:265",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703104,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780080,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:265",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780080,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868928,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/pool.c:265",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/swiotlb.c:swiotlb_alloc_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868928,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void * dma_alloc_from_pool(size_t size, struct page * * ret_page, gfp_t flags)
```

```json
{
  "name": "dma_alloc_from_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491299976,
      "name": "dma_alloc_from_pool",
      "external": true,
      "loc": "kernel/dma/remap.c:184",
      "file": "kernel/dma/remap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:arch_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491299976,
      "name": "dma_alloc_from_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
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
struct page * dma_alloc_from_pool(struct device * dev, size_t size, void * * cpu_addr, gfp_t gfp, bool (*)(struct device *, phys_addr_t, size_t) phys_addr_ok)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * dma_alloc_from_pool(size_t size, struct page * * ret_page, gfp_t flags)
```
</details>
</li>
</ul>

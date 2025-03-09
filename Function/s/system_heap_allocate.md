# Function: <code>system_heap_allocate</code>

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
int system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587407920,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:35",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407920,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
int system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587475872,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:334",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587475872,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
struct dma_buf * system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357616,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:334",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357616,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
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
struct dma_buf * system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:334",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923968,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
    },
    {
      "addr": 18446744071592524901,
      "name": "system_heap_allocate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct dma_buf * system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:335",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589275104,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1858
    },
    {
      "addr": 18446744071594396350,
      "name": "system_heap_allocate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
struct dma_buf * system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:338",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590839312,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
    },
    {
      "addr": 18446744071596259482,
      "name": "system_heap_allocate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct dma_buf * system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:337",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181584,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1623
    },
    {
      "addr": 18446744071596787591,
      "name": "system_heap_allocate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
struct dma_buf * system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```

```json
{
  "name": "system_heap_allocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "system_heap_allocate",
      "external": false,
      "loc": "drivers/dma-buf/heaps/system_heap.c:334",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591527680,
      "name": "system_heap_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1683
    },
    {
      "addr": 18446744071597696547,
      "name": "system_heap_allocate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int system_heap_allocate(struct dma_heap * heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct dma_buf *</code>
</li>
</ul>
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

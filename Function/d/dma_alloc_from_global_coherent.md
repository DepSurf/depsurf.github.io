# Function: <code>dma_alloc_from_global_coherent</code>

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
void * dma_alloc_from_global_coherent(ssize_t size, dma_addr_t * dma_handle)
```

```json
{
  "name": "dma_alloc_from_global_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039136,
      "name": "dma_alloc_from_global_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:194",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039136,
      "name": "dma_alloc_from_global_coherent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
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
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```

```json
{
  "name": "dma_alloc_from_global_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491293960,
      "name": "dma_alloc_from_global_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:183",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491293960,
      "name": "dma_alloc_from_global_coherent",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```

```json
{
  "name": "dma_alloc_from_global_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225298588,
      "name": "dma_alloc_from_global_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:183",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225298588,
      "name": "dma_alloc_from_global_coherent",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```

```json
{
  "name": "dma_alloc_from_global_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284219504,
      "name": "dma_alloc_from_global_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:183",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284219504,
      "name": "dma_alloc_from_global_coherent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```

```json
{
  "name": "dma_alloc_from_global_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271808514,
      "name": "dma_alloc_from_global_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:183",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271808514,
      "name": "dma_alloc_from_global_coherent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void * dma_alloc_from_global_coherent(ssize_t size, dma_addr_t * dma_handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void * dma_alloc_from_global_coherent(ssize_t size, dma_addr_t * dma_handle)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void * dma_alloc_from_global_coherent(struct device * dev, ssize_t size, dma_addr_t * dma_handle)
```
</details>
</li>
</ul>

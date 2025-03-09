# Function: <code>__dma_common_pages_remap</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_common_pages_remap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585096256,
      "name": "__dma_common_pages_remap",
      "external": false,
      "loc": "drivers/base/dma-mapping.c:254",
      "file": "drivers/base/dma-mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_common_pages_remap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585522016,
      "name": "__dma_common_pages_remap",
      "external": false,
      "loc": "drivers/base/dma-mapping.c:251",
      "file": "drivers/base/dma-mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_common_pages_remap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579945997,
      "name": "__dma_common_pages_remap",
      "external": false,
      "loc": "kernel/dma/mapping.c:248",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_common_contiguous_remap",
        "kernel/dma/mapping.c:dma_common_pages_remap"
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
struct vm_struct * __dma_common_pages_remap(struct page * * pages, size_t size, pgprot_t prot, const void * caller)
```

```json
{
  "name": "__dma_common_pages_remap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491299096,
      "name": "__dma_common_pages_remap",
      "external": false,
      "loc": "kernel/dma/remap.c:23",
      "file": "kernel/dma/remap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:dma_common_contiguous_remap",
        "kernel/dma/remap.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491299096,
      "name": "__dma_common_pages_remap",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vm_struct * __dma_common_pages_remap(struct page * * pages, size_t size, pgprot_t prot, const void * caller)
```

```json
{
  "name": "__dma_common_pages_remap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225299156,
      "name": "__dma_common_pages_remap",
      "external": false,
      "loc": "kernel/dma/remap.c:23",
      "file": "kernel/dma/remap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:dma_common_contiguous_remap",
        "kernel/dma/remap.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225299156,
      "name": "__dma_common_pages_remap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct vm_struct * __dma_common_pages_remap(struct page * * pages, size_t size, pgprot_t prot, const void * caller)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct vm_struct * __dma_common_pages_remap(struct page * * pages, size_t size, pgprot_t prot, const void * caller)
```
</details>
</li>
</ul>

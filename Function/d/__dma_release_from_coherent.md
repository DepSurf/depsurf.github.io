# Function: <code>__dma_release_from_coherent</code>

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
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```

```json
{
  "name": "__dma_release_from_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038112,
      "name": "__dma_release_from_coherent",
      "external": false,
      "loc": "kernel/dma/coherent.c:203",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_release_from_global_coherent",
        "kernel/dma/coherent.c:dma_release_from_dev_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038112,
      "name": "__dma_release_from_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```

```json
{
  "name": "__dma_release_from_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491293024,
      "name": "__dma_release_from_coherent",
      "external": false,
      "loc": "kernel/dma/coherent.c:193",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_release_from_global_coherent",
        "kernel/dma/coherent.c:dma_release_from_dev_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491293024,
      "name": "__dma_release_from_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```

```json
{
  "name": "__dma_release_from_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225297308,
      "name": "__dma_release_from_coherent",
      "external": false,
      "loc": "kernel/dma/coherent.c:193",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_release_from_global_coherent",
        "kernel/dma/coherent.c:dma_release_from_dev_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225297308,
      "name": "__dma_release_from_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```

```json
{
  "name": "__dma_release_from_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284217536,
      "name": "__dma_release_from_coherent",
      "external": false,
      "loc": "kernel/dma/coherent.c:193",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_release_from_global_coherent",
        "kernel/dma/coherent.c:dma_release_from_dev_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284217536,
      "name": "__dma_release_from_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```

```json
{
  "name": "__dma_release_from_coherent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271807308,
      "name": "__dma_release_from_coherent",
      "external": false,
      "loc": "kernel/dma/coherent.c:193",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_release_from_global_coherent",
        "kernel/dma/coherent.c:dma_release_from_dev_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271807308,
      "name": "__dma_release_from_coherent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
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
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int __dma_release_from_coherent(struct dma_coherent_mem * mem, int order, void * vaddr)
```
</details>
</li>
</ul>

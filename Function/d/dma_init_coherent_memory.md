# Function: <code>dma_init_coherent_memory</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_init_coherent_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038485,
      "name": "dma_init_coherent_memory",
      "external": false,
      "loc": "kernel/dma/coherent.c:40",
      "file": "kernel/dma/coherent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/coherent.c:dma_declare_coherent_memory"
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
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```

```json
{
  "name": "dma_init_coherent_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491292560,
      "name": "dma_init_coherent_memory",
      "external": false,
      "loc": "kernel/dma/coherent.c:40",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:rmem_dma_device_init",
        "kernel/dma/coherent.c:dma_declare_coherent_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491292560,
      "name": "dma_init_coherent_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```

```json
{
  "name": "dma_init_coherent_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225297660,
      "name": "dma_init_coherent_memory",
      "external": false,
      "loc": "kernel/dma/coherent.c:40",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:rmem_dma_device_init",
        "kernel/dma/coherent.c:dma_declare_coherent_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225297660,
      "name": "dma_init_coherent_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```

```json
{
  "name": "dma_init_coherent_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284218048,
      "name": "dma_init_coherent_memory",
      "external": false,
      "loc": "kernel/dma/coherent.c:40",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:rmem_dma_device_init",
        "kernel/dma/coherent.c:dma_declare_coherent_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284218048,
      "name": "dma_init_coherent_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```

```json
{
  "name": "dma_init_coherent_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271807926,
      "name": "dma_init_coherent_memory",
      "external": false,
      "loc": "kernel/dma/coherent.c:40",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:rmem_dma_device_init",
        "kernel/dma/coherent.c:dma_declare_coherent_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271807926,
      "name": "dma_init_coherent_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem * * mem)
```
</details>
</li>
</ul>

# Function: <code>dma_release_from_dev_coherent</code>

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
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```

```json
{
  "name": "dma_release_from_dev_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039184,
      "name": "dma_release_from_dev_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:231",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039184,
      "name": "dma_release_from_dev_coherent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```

```json
{
  "name": "dma_release_from_dev_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491294048,
      "name": "dma_release_from_dev_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:221",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491294048,
      "name": "dma_release_from_dev_coherent",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```

```json
{
  "name": "dma_release_from_dev_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225298656,
      "name": "dma_release_from_dev_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:221",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225298656,
      "name": "dma_release_from_dev_coherent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```

```json
{
  "name": "dma_release_from_dev_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284219568,
      "name": "dma_release_from_dev_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:221",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284219568,
      "name": "dma_release_from_dev_coherent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```

```json
{
  "name": "dma_release_from_dev_coherent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271808584,
      "name": "dma_release_from_dev_coherent",
      "external": true,
      "loc": "kernel/dma/coherent.c:221",
      "file": "kernel/dma/coherent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271808584,
      "name": "dma_release_from_dev_coherent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
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
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dma_release_from_dev_coherent(struct device * dev, int order, void * vaddr)
```
</details>
</li>
</ul>

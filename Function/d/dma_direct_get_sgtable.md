# Function: <code>dma_direct_get_sgtable</code>

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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148416,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:477",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148416,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128800,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:433",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128800,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133104,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:433",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133104,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276256,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:473",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276256,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580448048,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:505",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580448048,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692736,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:536",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692736,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769344,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:535",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769344,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855232,
      "name": "dma_direct_get_sgtable",
      "external": true,
      "loc": "kernel/dma/direct.c:524",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855232,
      "name": "dma_direct_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int dma_direct_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
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

# Function: <code>dma_contiguous_reserve_area</code>

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
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```

```json
{
  "name": "dma_contiguous_reserve_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510895828,
      "name": "dma_contiguous_reserve_area",
      "external": true,
      "loc": "kernel/dma/contiguous.c:162",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/contiguous.c:dma_contiguous_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510895828,
      "name": "dma_contiguous_reserve_area",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```

```json
{
  "name": "dma_contiguous_reserve_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243384160,
      "name": "dma_contiguous_reserve_area",
      "external": true,
      "loc": "kernel/dma/contiguous.c:162",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_reserve",
        "kernel/dma/contiguous.c:dma_contiguous_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243384160,
      "name": "dma_contiguous_reserve_area",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```

```json
{
  "name": "dma_contiguous_reserve_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270635022,
      "name": "dma_contiguous_reserve_area",
      "external": true,
      "loc": "kernel/dma/contiguous.c:162",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/contiguous.c:dma_contiguous_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270635022,
      "name": "dma_contiguous_reserve_area",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```

```json
{
  "name": "dma_contiguous_reserve_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604767464,
      "name": "dma_contiguous_reserve_area",
      "external": true,
      "loc": "kernel/dma/contiguous.c:162",
      "file": "kernel/dma/contiguous.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/contiguous.c:dma_contiguous_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604767464,
      "name": "dma_contiguous_reserve_area",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
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
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
int dma_contiguous_reserve_area(phys_addr_t size, phys_addr_t base, phys_addr_t limit, struct cma * * res_cma, bool fixed)
```
</details>
</li>
</ul>

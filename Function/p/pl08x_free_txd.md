# Function: <code>pl08x_free_txd</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pl08x_free_txd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498020800,
      "name": "pl08x_free_txd",
      "external": false,
      "loc": "drivers/dma/amba-pl08x.c:1492",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic",
        "drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg",
        "drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg",
        "drivers/dma/amba-pl08x.c:pl08x_init_txd",
        "drivers/dma/amba-pl08x.c:pl08x_init_txd",
        "drivers/dma/amba-pl08x.c:pl08x_init_txd",
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy",
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy",
        "drivers/dma/amba-pl08x.c:pl08x_desc_free",
        "drivers/dma/amba-pl08x.c:pl08x_desc_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498020800,
      "name": "pl08x_free_txd.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pl08x_free_txd(struct pl08x_driver_data * pl08x, struct pl08x_txd * txd)
```

```json
{
  "name": "pl08x_free_txd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230795100,
      "name": "pl08x_free_txd",
      "external": false,
      "loc": "drivers/dma/amba-pl08x.c:1492",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic",
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic",
        "drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg",
        "drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg",
        "drivers/dma/amba-pl08x.c:pl08x_init_txd",
        "drivers/dma/amba-pl08x.c:pl08x_init_txd",
        "drivers/dma/amba-pl08x.c:pl08x_init_txd",
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy",
        "drivers/dma/amba-pl08x.c:pl08x_desc_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230795100,
      "name": "pl08x_free_txd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void pl08x_free_txd(struct pl08x_driver_data * pl08x, struct pl08x_txd * txd)
```
</details>
</li>
</ul>

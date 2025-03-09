# Function: <code>ldma_prep_slave_sg</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct dma_async_tx_descriptor * ldma_prep_slave_sg(struct dma_chan * chan, struct scatterlist * sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void * context)
```

```json
{
  "name": "ldma_prep_slave_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldma_prep_slave_sg",
      "external": false,
      "loc": "drivers/dma/lgm/lgm-dma.c:1157",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219536,
      "name": "ldma_prep_slave_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 885
    },
    {
      "addr": 18446744071591387195,
      "name": "ldma_prep_slave_sg.cold",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dma_async_tx_descriptor * ldma_prep_slave_sg(struct dma_chan * chan, struct scatterlist * sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void * context)
```

```json
{
  "name": "ldma_prep_slave_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldma_prep_slave_sg",
      "external": false,
      "loc": "drivers/dma/lgm/lgm-dma.c:1157",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586726960,
      "name": "ldma_prep_slave_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    },
    {
      "addr": 18446744071592427898,
      "name": "ldma_prep_slave_sg.cold",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct dma_async_tx_descriptor * ldma_prep_slave_sg(struct dma_chan * chan, struct scatterlist * sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void * context)
```

```json
{
  "name": "ldma_prep_slave_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldma_prep_slave_sg",
      "external": false,
      "loc": "drivers/dma/lgm/lgm-dma.c:1157",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000000,
      "name": "ldma_prep_slave_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
    },
    {
      "addr": 18446744071594296026,
      "name": "ldma_prep_slave_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct dma_async_tx_descriptor * ldma_prep_slave_sg(struct dma_chan * chan, struct scatterlist * sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void * context)
```

```json
{
  "name": "ldma_prep_slave_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589370816,
      "name": "ldma_prep_slave_sg",
      "external": false,
      "loc": "drivers/dma/lgm/lgm-dma.c:1157",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370816,
      "name": "ldma_prep_slave_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
struct dma_async_tx_descriptor * ldma_prep_slave_sg(struct dma_chan * chan, struct scatterlist * sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void * context)
```

```json
{
  "name": "ldma_prep_slave_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589669456,
      "name": "ldma_prep_slave_sg",
      "external": false,
      "loc": "drivers/dma/lgm/lgm-dma.c:1157",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669456,
      "name": "ldma_prep_slave_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
struct dma_async_tx_descriptor * ldma_prep_slave_sg(struct dma_chan * chan, struct scatterlist * sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void * context)
```

```json
{
  "name": "ldma_prep_slave_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589980064,
      "name": "ldma_prep_slave_sg",
      "external": false,
      "loc": "drivers/dma/lgm/lgm-dma.c:1157",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589980064,
      "name": "ldma_prep_slave_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct dma_async_tx_descriptor * ldma_prep_slave_sg(struct dma_chan * chan, struct scatterlist * sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void * context)
```
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

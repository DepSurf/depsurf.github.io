# Function: <code>mv_xor_prep_dma_xor</code>

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
struct dma_async_tx_descriptor * mv_xor_prep_dma_xor(struct dma_chan * chan, dma_addr_t dest, dma_addr_t * src, unsigned int src_cnt, size_t len, long unsigned int flags)
```

```json
{
  "name": "mv_xor_prep_dma_xor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498045224,
      "name": "mv_xor_prep_dma_xor",
      "external": false,
      "loc": "drivers/dma/mv_xor.c:555",
      "file": "drivers/dma/mv_xor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_prep_dma_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498045224,
      "name": "mv_xor_prep_dma_xor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
struct dma_async_tx_descriptor * mv_xor_prep_dma_xor(struct dma_chan * chan, dma_addr_t dest, dma_addr_t * src, unsigned int src_cnt, size_t len, long unsigned int flags)
```

```json
{
  "name": "mv_xor_prep_dma_xor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230813668,
      "name": "mv_xor_prep_dma_xor",
      "external": false,
      "loc": "drivers/dma/mv_xor.c:555",
      "file": "drivers/dma/mv_xor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_chan_xor_self_test",
        "drivers/dma/mv_xor.c:mv_xor_prep_dma_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230813668,
      "name": "mv_xor_prep_dma_xor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
struct dma_async_tx_descriptor * mv_xor_prep_dma_xor(struct dma_chan * chan, dma_addr_t dest, dma_addr_t * src, unsigned int src_cnt, size_t len, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct dma_async_tx_descriptor * mv_xor_prep_dma_xor(struct dma_chan * chan, dma_addr_t dest, dma_addr_t * src, unsigned int src_cnt, size_t len, long unsigned int flags)
```
</details>
</li>
</ul>

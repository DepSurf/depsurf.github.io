# Function: <code>mv_chan_start_new_chain</code>

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
void mv_chan_start_new_chain(struct mv_xor_chan * mv_chan, struct mv_xor_desc_slot * sw_desc)
```

```json
{
  "name": "mv_chan_start_new_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498044144,
      "name": "mv_chan_start_new_chain",
      "external": false,
      "loc": "drivers/dma/mv_xor.c:178",
      "file": "drivers/dma/mv_xor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_tx_submit",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498044144,
      "name": "mv_chan_start_new_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void mv_chan_start_new_chain(struct mv_xor_chan * mv_chan, struct mv_xor_desc_slot * sw_desc)
```

```json
{
  "name": "mv_chan_start_new_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230809896,
      "name": "mv_chan_start_new_chain",
      "external": false,
      "loc": "drivers/dma/mv_xor.c:178",
      "file": "drivers/dma/mv_xor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_tx_submit",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230809896,
      "name": "mv_chan_start_new_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void mv_chan_start_new_chain(struct mv_xor_chan * mv_chan, struct mv_xor_desc_slot * sw_desc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mv_chan_start_new_chain(struct mv_xor_chan * mv_chan, struct mv_xor_desc_slot * sw_desc)
```
</details>
</li>
</ul>

# Function: <code>xsk_tx_peek_release_desc_batch</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, struct xdp_desc * descs, u32 max_entries)
```

```json
{
  "name": "xsk_tx_peek_release_desc_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591130176,
      "name": "xsk_tx_peek_release_desc_batch",
      "external": true,
      "loc": "net/xdp/xsk.c:358",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591130176,
      "name": "xsk_tx_peek_release_desc_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, struct xdp_desc * descs, u32 max_entries)
```

```json
{
  "name": "xsk_tx_peek_release_desc_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591060512,
      "name": "xsk_tx_peek_release_desc_batch",
      "external": true,
      "loc": "net/xdp/xsk.c:373",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591060512,
      "name": "xsk_tx_peek_release_desc_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, struct xdp_desc * descs, u32 max_entries)
```

```json
{
  "name": "xsk_tx_peek_release_desc_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_release_desc_batch",
      "external": true,
      "loc": "net/xdp/xsk.c:373",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592751224,
      "name": "xsk_tx_peek_release_desc_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071591902704,
      "name": "xsk_tx_peek_release_desc_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, u32 max_entries)
```

```json
{
  "name": "xsk_tx_peek_release_desc_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_release_desc_batch",
      "external": true,
      "loc": "net/xdp/xsk.c:358",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594637776,
      "name": "xsk_tx_peek_release_desc_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071593621136,
      "name": "xsk_tx_peek_release_desc_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, u32 nb_pkts)
```

```json
{
  "name": "xsk_tx_peek_release_desc_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_release_desc_batch",
      "external": true,
      "loc": "net/xdp/xsk.c:358",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596367185,
      "name": "xsk_tx_peek_release_desc_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071595549648,
      "name": "xsk_tx_peek_release_desc_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, u32 nb_pkts)
```

```json
{
  "name": "xsk_tx_peek_release_desc_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_release_desc_batch",
      "external": true,
      "loc": "net/xdp/xsk.c:359",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596896920,
      "name": "xsk_tx_peek_release_desc_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071596057840,
      "name": "xsk_tx_peek_release_desc_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, u32 nb_pkts)
```

```json
{
  "name": "xsk_tx_peek_release_desc_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_release_desc_batch",
      "external": true,
      "loc": "net/xdp/xsk.c:489",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597822249,
      "name": "xsk_tx_peek_release_desc_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071596923968,
      "name": "xsk_tx_peek_release_desc_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
u32 xsk_tx_peek_release_desc_batch(struct xsk_buff_pool * pool, struct xdp_desc * descs, u32 max_entries)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct xdp_desc * descs</code>
</li>
<li>
<b>Param reordered. </b>
<code>pool, descs, max_entries</code> ➡️ <code>pool, max_entries</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 nb_pkts</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 max_entries</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

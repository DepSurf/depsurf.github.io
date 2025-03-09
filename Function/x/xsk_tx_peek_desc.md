# Function: <code>xsk_tx_peek_desc</code>

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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_tx_peek_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591129712,
      "name": "xsk_tx_peek_desc",
      "external": true,
      "loc": "net/xdp/xsk.c:316",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_tx_peek_release_desc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591129712,
      "name": "xsk_tx_peek_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_tx_peek_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591060016,
      "name": "xsk_tx_peek_desc",
      "external": true,
      "loc": "net/xdp/xsk.c:331",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_tx_peek_release_desc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591060016,
      "name": "xsk_tx_peek_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_tx_peek_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_desc",
      "external": true,
      "loc": "net/xdp/xsk.c:331",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_tx_peek_release_desc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592751185,
      "name": "xsk_tx_peek_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071591902160,
      "name": "xsk_tx_peek_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_tx_peek_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_desc",
      "external": true,
      "loc": "net/xdp/xsk.c:316",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_tx_peek_release_desc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594637747,
      "name": "xsk_tx_peek_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071593620544,
      "name": "xsk_tx_peek_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_tx_peek_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_desc",
      "external": true,
      "loc": "net/xdp/xsk.c:316",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_tx_peek_release_desc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596367156,
      "name": "xsk_tx_peek_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071595549040,
      "name": "xsk_tx_peek_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_tx_peek_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_desc",
      "external": true,
      "loc": "net/xdp/xsk.c:317",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_tx_peek_release_desc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596896891,
      "name": "xsk_tx_peek_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071596057296,
      "name": "xsk_tx_peek_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
```

```json
{
  "name": "xsk_tx_peek_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_tx_peek_desc",
      "external": true,
      "loc": "net/xdp/xsk.c:429",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_tx_peek_release_desc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597822208,
      "name": "xsk_tx_peek_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071596923264,
      "name": "xsk_tx_peek_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
bool xsk_tx_peek_desc(struct xsk_buff_pool * pool, struct xdp_desc * desc)
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

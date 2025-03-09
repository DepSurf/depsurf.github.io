# Function: <code>wakeup_kcompactd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755040,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:1960",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755040,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820256,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:1945",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820256,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860736,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:1994",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860736,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951712,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2017",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951712,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087824,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2025",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087824,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165744,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2026",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165744,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236704,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2607",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236704,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295168,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295168,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485264,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2615",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485264,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581527024,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2811",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527024,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549168,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2856",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549168,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812896,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2873",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812896,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202064,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2893",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202064,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582688768,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2892",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688768,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582897952,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2987",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897952,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069824,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:3046",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069824,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492701808,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492701808,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226540076,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226540076,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286036192,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286036192,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272702810,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272702810,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264016,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264016,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210672,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210672,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581255216,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255216,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "wakeup_kcompactd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319120,
      "name": "wakeup_kcompactd",
      "external": true,
      "loc": "mm/compaction.c:2598",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319120,
      "name": "wakeup_kcompactd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void wakeup_kcompactd(pg_data_t * pgdat, int order, int classzone_idx)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

# Function: <code>gnttab_foreach_grant_in_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847872,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:779",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_make_txreqs",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847872,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178576,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:778",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178576,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584359952,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:778",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584359952,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584441568,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:779",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584441568,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849888,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:871",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849888,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585078864,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:871",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078864,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585192336,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:984",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585192336,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585405760,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:984",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585405760,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585546496,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:984",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546496,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586260960,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:982",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260960,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586379120,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:1105",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586379120,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586262976,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:1105",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262976,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586773632,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:1112",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773632,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588051904,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:1178",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051904,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431216,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:1181",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431216,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589730352,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:1199",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589730352,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068320,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:1197",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068320,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498199584,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:984",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498199584,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585308528,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:984",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585308528,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585496896,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:984",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496896,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```

```json
{
  "name": "gnttab_foreach_grant_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585604928,
      "name": "gnttab_foreach_grant_in_range",
      "external": true,
      "loc": "drivers/xen/grant-table.c:984",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_make_txreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604928,
      "name": "gnttab_foreach_grant_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void gnttab_foreach_grant_in_range(struct page * page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void * data)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

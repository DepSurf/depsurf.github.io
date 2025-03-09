# Function: <code>gnttab_grant_foreign_access_ref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583844560,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:235",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844560,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584176380,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:234",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174160,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584357772,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:234",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355552,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584439244,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:235",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437040,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584847900,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:261",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845552,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585083842,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:261",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076512,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585191826,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:265",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186144,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585403328,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:265",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398256,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585545088,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:265",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585538992,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586262400,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:264",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257088,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586380672,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:264",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375136,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586264720,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:264",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586259616,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586775776,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:261",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770192,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588054573,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:405",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048208,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589433405,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:405",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427024,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589732525,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:405",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726176,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590070493,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:405",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064160,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498208516,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:265",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498198944,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585307120,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:265",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301024,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585495488,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:265",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585489392,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```

```json
{
  "name": "gnttab_grant_foreign_access_ref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585603520,
      "name": "gnttab_grant_foreign_access_ref",
      "external": true,
      "loc": "drivers/xen/grant-table.c:265",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_grant_foreign_access"
      ],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597392,
      "name": "gnttab_grant_foreign_access_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
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
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly)
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

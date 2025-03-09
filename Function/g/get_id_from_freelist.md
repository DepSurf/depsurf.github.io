# Function: <code>get_id_from_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_info * info)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584558528,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:204",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    },
    {
      "addr": 18446744071585112635,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:189",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558528,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584908928,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:262",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    },
    {
      "addr": 18446744071585505531,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:189",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584908928,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585092560,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:262",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    },
    {
      "addr": 18446744071585693211,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:189",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585092560,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585175072,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:266",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    },
    {
      "addr": 18446744071585780187,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:190",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175072,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585603312,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:266",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    },
    {
      "addr": 18446744071586218555,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585603312,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585847792,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:266",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    },
    {
      "addr": 18446744071586475787,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847792,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585982656,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:265",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    },
    {
      "addr": 18446744071586623515,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982656,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586226160,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:265",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    },
    {
      "addr": 18446744071586876955,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226160,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586374384,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:265",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    },
    {
      "addr": 18446744071587022987,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374384,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587147520,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:276",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_discard_req"
      ]
    },
    {
      "addr": 18446744071587854331,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:194",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147520,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587231808,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:276",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_discard_req"
      ]
    },
    {
      "addr": 18446744071587911019,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:206",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587231808,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587120480,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:276",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    },
    {
      "addr": 18446744071587793771,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:206",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120480,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587695792,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:279",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695792,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589039552,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:283",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589039552,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590568384,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:286",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590568384,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590909536,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:286",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590909536,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591253280,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:286",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591253280,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499220960,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:265",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    },
    {
      "addr": 18446603336500142868,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499220960,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586137024,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:280",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    },
    {
      "addr": 18446744071586780011,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:209",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137024,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586322352,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:265",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    },
    {
      "addr": 18446744071586977547,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586322352,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "get_id_from_freelist",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586433920,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:265",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req"
      ]
    },
    {
      "addr": 18446744071587084747,
      "name": "get_id_from_freelist",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:192",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_tx_setup_grant"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586433920,
      "name": "get_id_from_freelist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blkfront_ring_info * rinfo</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blkfront_info * info</code>
</li>
</ul>
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
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
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
int get_id_from_freelist(struct blkfront_ring_info * rinfo)
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

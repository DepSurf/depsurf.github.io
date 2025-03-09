# Function: <code>xenbus_unmap_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871536,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:886",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871536,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202256,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:886",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202256,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584383712,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:886",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383712,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584466429,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:867",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465840,
      "name": "xenbus_unmap_ring.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071584466192,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584876806,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:874",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584876224,
      "name": "xenbus_unmap_ring.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071584876576,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585110909,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:874",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585106704,
      "name": "xenbus_unmap_ring.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071585107056,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585221693,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:872",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217472,
      "name": "xenbus_unmap_ring.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071585217824,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585433919,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:872",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585429776,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071585430112,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585574367,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:872",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585570224,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071585570560,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586295135,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:567",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291872,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586414287,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:570",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410976,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586298431,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:570",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295008,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586817647,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:567",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813280,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588099200,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:609",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099200,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589484064,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:612",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589484064,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589784528,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:612",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589784528,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590120336,
      "name": "xenbus_unmap_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:623",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120336,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498239156,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:872",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498234952,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446603336498235328,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585336399,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:872",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585332256,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071585332592,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585524767,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:872",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520624,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071585520960,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```

```json
{
  "name": "xenbus_unmap_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629754,
      "name": "xenbus_unmap_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:872",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629120,
      "name": "xenbus_unmap_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071585629456,
      "name": "xenbus_unmap_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```
</details>
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
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
int xenbus_unmap_ring(struct xenbus_device * dev, grant_handle_t * handles, unsigned int nr_handles, long unsigned int * vaddrs)
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

# Function: <code>xenbus_map_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875072,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:710",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875072,
      "name": "xenbus_map_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205792,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:710",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205792,
      "name": "xenbus_map_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387248,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:710",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387248,
      "name": "xenbus_map_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584468512,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:691",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468512,
      "name": "xenbus_map_ring.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584468640,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584878880,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:633",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584878880,
      "name": "xenbus_map_ring.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584879008,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585108960,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:633",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108960,
      "name": "xenbus_map_ring.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071585109088,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585219728,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:631",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219728,
      "name": "xenbus_map_ring.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071585219856,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585431936,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:631",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431936,
      "name": "xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585432064,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585572384,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:631",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572384,
      "name": "xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585572512,
      "name": "xenbus_map_ring",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498237784,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:631",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498237784,
      "name": "xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446603336498237984,
      "name": "xenbus_map_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585334416,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:631",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334416,
      "name": "xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585334544,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585522784,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:631",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522784,
      "name": "xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585522912,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```

```json
{
  "name": "xenbus_map_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585631680,
      "name": "xenbus_map_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:631",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631680,
      "name": "xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585631808,
      "name": "xenbus_map_ring",
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```
</details>
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
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
int xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, long unsigned int * vaddrs, bool * leaked)
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

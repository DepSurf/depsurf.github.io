# Function: <code>xenbus_grant_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875840,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:380",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875840,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206560,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:380",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206560,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388016,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:380",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388016,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469792,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:361",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469792,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584880160,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:361",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584880160,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585109728,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:361",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585109728,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585220512,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:359",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220512,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432704,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:359",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432704,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585573152,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:359",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585573152,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586294480,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:375",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586294480,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586413632,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:378",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586413632,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586297440,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:378",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586297440,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816224,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:378",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816224,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
    }
  ]
}
```
</details>
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498236600,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:359",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498236600,
      "name": "xenbus_grant_ring",
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585335184,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:359",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585335184,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523552,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:359",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523552,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```

```json
{
  "name": "xenbus_grant_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585632928,
      "name": "xenbus_grant_ring",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:359",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632928,
      "name": "xenbus_grant_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
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
int xenbus_grant_ring(struct xenbus_device * dev, void * vaddr, unsigned int nr_pages, grant_ref_t * grefs)
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

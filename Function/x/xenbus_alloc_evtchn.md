# Function: <code>xenbus_alloc_evtchn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874080,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:415",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874080,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204800,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:415",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204800,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386256,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:415",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386256,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467600,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:396",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467600,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877968,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:396",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877968,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585108032,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:396",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108032,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218800,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:394",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218800,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585431104,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:394",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431104,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585571552,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:394",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571552,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586292720,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:416",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront_split",
        "drivers/net/xen-netfront.c:setup_netfront_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292720,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586411840,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:419",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront_split",
        "drivers/net/xen-netfront.c:setup_netfront_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411840,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586295680,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:419",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295680,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586814288,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:417",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814288,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588096064,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:459",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588096064,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589480528,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:462",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480528,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780880,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:462",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780880,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, evtchn_port_t * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116912,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:471",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116912,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498236920,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:394",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498236920,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585333584,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:394",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333584,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521952,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:394",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521952,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```

```json
{
  "name": "xenbus_alloc_evtchn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585630848,
      "name": "xenbus_alloc_evtchn",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:394",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630848,
      "name": "xenbus_alloc_evtchn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int * port</code> ➡️ <code>evtchn_port_t * port</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
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
int xenbus_alloc_evtchn(struct xenbus_device * dev, int * port)
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

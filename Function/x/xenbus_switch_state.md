# Function: <code>xenbus_switch_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583873584,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/net/xen-netfront.c:netback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873584,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584204418,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204304,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584385874,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385760,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584467214,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467104,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584877582,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877472,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585107650,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585107536,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585218418,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218304,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430707,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585430592,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585571155,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571040,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586292547,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:263",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_closing",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291840,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586411651,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:266",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_closing",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_xdp",
        "drivers/net/xen-netfront.c:xennet_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410944,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586295491,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:266",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_xdp",
        "drivers/net/xen-netfront.c:xennet_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586294768,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586814099,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:266",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813040,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588095834,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:266",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095440,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589480266,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:266",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589479824,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589780618,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:266",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780176,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590116650,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:275",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_create_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116208,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498236148,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498235952,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585333187,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_freeze",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_restore",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333072,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585521555,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521440,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```

```json
{
  "name": "xenbus_switch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585630451,
      "name": "xenbus_switch_state",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:247",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_backend_changed",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630336,
      "name": "xenbus_switch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
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
int xenbus_switch_state(struct xenbus_device * dev, enum xenbus_state state)
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

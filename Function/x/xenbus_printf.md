# Function: <code>xenbus_printf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881872,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:568",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881872,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212480,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:563",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212480,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584393952,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:578",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393952,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478336,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:595",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478336,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584888608,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:598",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584888608,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119664,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:600",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119664,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585230432,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:600",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585230432,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585442592,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:603",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585442592,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585583024,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585583024,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304944,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304944,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586423664,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:xennet_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423664,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586307056,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:xennet_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586307056,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826656,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826656,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588110080,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588110080,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495712,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495712,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589796512,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589796512,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132736,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132736,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498247592,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498247592,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585345056,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585345056,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533424,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533424,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585641424,
      "name": "xenbus_printf",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:606",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_event",
        "drivers/xen/manage.c:sysrq_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585641424,
      "name": "xenbus_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
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
int xenbus_printf(struct xenbus_transaction t, const char * dir, const char * node, const char * fmt, void (anon))
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

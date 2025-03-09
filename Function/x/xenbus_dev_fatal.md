# Function: <code>xenbus_dev_fatal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873616,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:339",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring",
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:talk_to_netback",
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
      "addr": 18446744071583873616,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204336,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:339",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204336,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385792,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:339",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385792,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467136,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:320",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467136,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877504,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:320",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877504,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585107568,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:320",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585107568,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218336,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218336,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585430624,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585430624,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585571072,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571072,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586292464,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:334",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292464,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586411568,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:337",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411568,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586295408,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:337",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295408,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586814016,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:337",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814016,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095744,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:337",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095744,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589480176,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:337",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480176,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780528,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:337",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780528,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116560,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:346",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:write_queue_xenstore_keys",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116560,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498236024,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498236024,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585333104,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333104,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521472,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521472,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_fatal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585630368,
      "name": "xenbus_dev_fatal",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path",
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:write_per_ring_nodes",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630368,
      "name": "xenbus_dev_fatal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
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
void xenbus_dev_fatal(struct xenbus_device * dev, int err, const char * fmt, void (anon))
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

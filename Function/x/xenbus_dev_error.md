# Function: <code>xenbus_dev_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871424,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871424,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202144,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202144,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584383600,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:318",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383600,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584464912,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:299",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464912,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584875296,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:299",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875296,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585106352,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:299",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585106352,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217120,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:297",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217120,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585429456,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:297",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585429456,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585569904,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:297",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585569904,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586291072,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:313",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkfront_closing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291072,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586410112,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:316",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkfront_closing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410112,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293936,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:316",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293936,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586812176,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:316",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586812176,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095472,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:316",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095472,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589479872,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:316",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589479872,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589780224,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:316",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780224,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116256,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:325",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116256,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498234528,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:297",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498234528,
      "name": "xenbus_dev_error",
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585331936,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:297",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkfront_freeze",
        "drivers/block/xen-blkfront.c:blkfront_freeze",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331936,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520304,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:297",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520304,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "xenbus_dev_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628352,
      "name": "xenbus_dev_error",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_client.c:297",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628352,
      "name": "xenbus_dev_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
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
void xenbus_dev_error(struct xenbus_device * dev, int err, const char * fmt, void (anon))
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

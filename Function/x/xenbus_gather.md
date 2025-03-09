# Function: <code>xenbus_gather</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882064,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882064,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212672,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:586",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212672,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584394144,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:601",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394144,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584477200,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:618",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477200,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584887616,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:621",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887616,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118688,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:623",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118688,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585229456,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:623",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229456,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585441616,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:626",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441616,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585582048,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585582048,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303600,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303600,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422320,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422320,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586305888,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305888,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586825488,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586825488,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588109008,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109008,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589494576,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589494576,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589795376,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795376,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590131600,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131600,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498246448,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498246448,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585344080,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585344080,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585532448,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532448,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```

```json
{
  "name": "xenbus_gather",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640448,
      "name": "xenbus_gather",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:629",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640448,
      "name": "xenbus_gather",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
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
int xenbus_gather(struct xenbus_transaction t, const char * dir, void (anon))
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

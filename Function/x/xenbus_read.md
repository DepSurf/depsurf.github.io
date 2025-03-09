# Function: <code>xenbus_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880432,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:428",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880432,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211056,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:423",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211056,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584392432,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:423",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392432,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476832,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:449",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476832,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584887248,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:452",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887248,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118320,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:454",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118320,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585229088,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:454",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229088,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585441232,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:457",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441232,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585581664,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581664,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586303773,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302896,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586422493,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421616,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586306061,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305184,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586825661,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824784,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588109194,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588108416,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589494762,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589493904,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589795562,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589794704,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590131786,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf"
      ],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130928,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498245944,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498245944,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585343696,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343696,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585532064,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532064,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```

```json
{
  "name": "xenbus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640064,
      "name": "xenbus_read",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:460",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_gather",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/xen/sys-hypervisor.c:uuid_show",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640064,
      "name": "xenbus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
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
void * xenbus_read(struct xenbus_transaction t, const char * dir, const char * node, unsigned int * len)
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

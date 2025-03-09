# Function: <code>xenbus_read_unsigned</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584397817,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:563",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393856,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584480520,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:580",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477104,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584890792,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:583",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887520,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585121803,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:585",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118592,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585232571,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:585",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229360,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585444708,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:588",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441520,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585585140,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581952,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586304568,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304400,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586423288,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423120,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586309385,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306688,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586828985,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826288,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588112812,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109696,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589498621,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495296,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589799421,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589796096,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590135645,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:negotiate_mq",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132320,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498250184,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498246320,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585347172,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343984,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585535540,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532352,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```

```json
{
  "name": "xenbus_read_unsigned",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585643524,
      "name": "xenbus_read_unsigned",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:591",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features",
        "drivers/net/xen-netfront.c:xennet_fix_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640352,
      "name": "xenbus_read_unsigned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```
</details>
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
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
unsigned int xenbus_read_unsigned(const char * dir, const char * node, unsigned int default_val)
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

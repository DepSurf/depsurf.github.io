# Function: <code>xenbus_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880752,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:447",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880752,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211152,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:442",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211152,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584392528,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:442",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392528,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478112,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:468",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478112,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584888384,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:471",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584888384,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119456,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:473",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119456,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585230224,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:473",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585230224,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585442384,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:476",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585442384,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585582816,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585582816,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304672,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304672,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586423392,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423392,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586306784,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306784,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826384,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826384,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588109824,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109824,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495440,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495440,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589796240,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589796240,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132464,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132464,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498247360,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498247360,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585344848,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585344848,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533216,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533216,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```

```json
{
  "name": "xenbus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585641216,
      "name": "xenbus_write",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:479",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/manage.c:shutdown_handler",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_printf",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585641216,
      "name": "xenbus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
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
int xenbus_write(struct xenbus_transaction t, const char * dir, const char * node, const char * string)
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

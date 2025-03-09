# Function: <code>tun_ptr_free</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586429232,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:658",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586429232,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574480,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:658",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574480,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826064,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826064,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586972160,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972160,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587819446,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:620",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587798144,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587876564,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:591",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856032,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587755348,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:599",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735376,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588352947,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:605",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588330608,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589741141,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:610",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724192,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591359653,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:610",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591344016,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591720325,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:610",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591705664,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592464005,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:610",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592449280,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499964304,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499964304,
      "name": "tun_ptr_free",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232502764,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232502764,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293290832,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293290832,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277043062,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277043062,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586729168,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729168,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586596384,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596384,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586926720,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926720,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void tun_ptr_free(void * ptr)
```

```json
{
  "name": "tun_ptr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033168,
      "name": "tun_ptr_free",
      "external": true,
      "loc": "drivers/net/tun.c:652",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033168,
      "name": "tun_ptr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void tun_ptr_free(void * ptr)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

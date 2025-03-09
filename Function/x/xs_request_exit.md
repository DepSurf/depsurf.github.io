# Function: <code>xs_request_exit</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584475488,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:138",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475488,
      "name": "xs_request_exit",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584885904,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:138",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584885904,
      "name": "xs_request_exit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116960,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:138",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116960,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585227728,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:138",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585227728,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585439808,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439808,
      "name": "xs_request_exit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585580240,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580240,
      "name": "xs_request_exit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586301824,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586301824,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420544,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420544,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303760,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303760,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592435926,
      "name": "xs_request_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586823312,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594303931,
      "name": "xs_request_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588106912,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596230861,
      "name": "xs_request_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589492272,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596758769,
      "name": "xs_request_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589793104,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597667191,
      "name": "xs_request_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590129280,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498244240,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498244240,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585342272,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585342272,
      "name": "xs_request_exit",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530640,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530640,
      "name": "xs_request_exit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```

```json
{
  "name": "xs_request_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585638672,
      "name": "xs_request_exit",
      "external": true,
      "loc": "drivers/xen/xenbus/xenbus_xs.c:139",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_talkv",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638672,
      "name": "xs_request_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```
</details>
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
void xs_request_exit(struct xb_req_data * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xs_request_exit(struct xb_req_data * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xs_request_exit(struct xb_req_data * req)
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
void xs_request_exit(struct xb_req_data * req)
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

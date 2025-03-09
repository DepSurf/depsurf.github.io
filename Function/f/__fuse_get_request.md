# Function: <code>__fuse_get_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582047707,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:116",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:__fuse_request_send"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060816,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582261419,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:103",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:__fuse_request_send"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274928,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582351355,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:103",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:__fuse_request_send"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364336,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582436443,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:104",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:__fuse_request_send"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448688,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598272,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:104",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:__fuse_request_send",
        "fs/fuse/file.c:fuse_async_req_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598272,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790848,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:107",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_send_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790848,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888128,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:143",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/file.c:fuse_async_req_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888128,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069488,
      "name": "__fuse_get_request",
      "external": true,
      "loc": "fs/fuse/dev.c:143",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/file.c:fuse_async_req_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069488,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166640,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166640,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583494113,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583602497,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:67",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:__fuse_request_send"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583625159,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:67",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583984183,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:67",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584565199,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:67",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585244627,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:67",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585474767,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:67",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585709791,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:67",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494895968,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228309292,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288760256,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274201476,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583135376,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135376,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072528,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072528,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583119408,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119408,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __fuse_get_request(struct fuse_req * req)
```

```json
{
  "name": "__fuse_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213152,
      "name": "__fuse_get_request",
      "external": false,
      "loc": "fs/fuse/dev.c:66",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213152,
      "name": "__fuse_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __fuse_get_request(struct fuse_req * req)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __fuse_get_request(struct fuse_req * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __fuse_get_request(struct fuse_req * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __fuse_get_request(struct fuse_req * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __fuse_get_request(struct fuse_req * req)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

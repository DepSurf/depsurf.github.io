# Function: <code>__fuse_request_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582047600,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:485",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_request_send",
        "fs/fuse/dev.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047600,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261312,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:460",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261312,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582351248,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:464",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351248,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436336,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:464",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436336,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598304,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:464",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598304,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582790880,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:477",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790880,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582888160,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:533",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888160,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583069520,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:557",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069520,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583181864,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583505930,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_req * req)
```

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583604192,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:414",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604192,
      "name": "__fuse_request_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583637377,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:414",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583996529,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:414",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584580256,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:410",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585257523,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:410",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585487149,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:410",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585722509,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:410",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494897704,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228310960,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288762532,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274211626,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583150600,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583087752,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583134632,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fuse_request_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583228216,
      "name": "__fuse_request_send",
      "external": false,
      "loc": "fs/fuse/dev.c:405",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void __fuse_request_send(struct fuse_conn * fc, struct fuse_req * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __fuse_request_send(struct fuse_req * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void __fuse_request_send(struct fuse_req * req)
```
</details>
</li>
</ul>

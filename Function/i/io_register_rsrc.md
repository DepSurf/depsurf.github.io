# Function: <code>io_register_rsrc</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int io_register_rsrc(struct io_ring_ctx * ctx, void * arg, unsigned int size, unsigned int type)
```

```json
{
  "name": "io_register_rsrc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616448,
      "name": "io_register_rsrc",
      "external": false,
      "loc": "fs/io_uring.c:9974",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616448,
      "name": "io_register_rsrc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int io_register_rsrc(struct io_ring_ctx * ctx, void * arg, unsigned int size, unsigned int type)
```

```json
{
  "name": "io_register_rsrc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960256,
      "name": "io_register_rsrc",
      "external": false,
      "loc": "fs/io_uring.c:10647",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960256,
      "name": "io_register_rsrc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int io_register_rsrc(struct io_ring_ctx * ctx, void * arg, unsigned int size, unsigned int type)
```

```json
{
  "name": "io_register_rsrc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594120841,
      "name": "io_register_rsrc",
      "external": false,
      "loc": "io_uring/io_uring.c:12339",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594120841,
      "name": "io_register_rsrc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int io_register_rsrc(struct io_ring_ctx * ctx, void * arg, unsigned int size, unsigned int type)
```

```json
{
  "name": "io_register_rsrc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586852336,
      "name": "io_register_rsrc",
      "external": true,
      "loc": "io_uring/rsrc.c:639",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852336,
      "name": "io_register_rsrc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int io_register_rsrc(struct io_ring_ctx * ctx, void * arg, unsigned int size, unsigned int type)
```

```json
{
  "name": "io_register_rsrc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587118480,
      "name": "io_register_rsrc",
      "external": true,
      "loc": "io_uring/rsrc.c:527",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118480,
      "name": "io_register_rsrc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int io_register_rsrc(struct io_ring_ctx * ctx, void * arg, unsigned int size, unsigned int type)
```

```json
{
  "name": "io_register_rsrc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587397184,
      "name": "io_register_rsrc",
      "external": true,
      "loc": "io_uring/rsrc.c:522",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/register.c:__io_uring_register",
        "io_uring/register.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397184,
      "name": "io_register_rsrc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int io_register_rsrc(struct io_ring_ctx * ctx, void * arg, unsigned int size, unsigned int type)
```
</details>
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

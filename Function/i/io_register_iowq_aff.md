# Function: <code>io_register_iowq_aff</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_register_iowq_aff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582903440,
      "name": "io_register_iowq_aff",
      "external": false,
      "loc": "fs/io_uring.c:10673",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903440,
      "name": "io_register_iowq_aff.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_register_iowq_aff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594112472,
      "name": "io_register_iowq_aff",
      "external": false,
      "loc": "io_uring/io_uring.c:12371",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594112472,
      "name": "io_register_iowq_aff.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_register_iowq_aff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586745952,
      "name": "io_register_iowq_aff",
      "external": false,
      "loc": "io_uring/io_uring.c:3887",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586745952,
      "name": "io_register_iowq_aff.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int io_register_iowq_aff(struct io_ring_ctx * ctx, void * arg, unsigned int len)
```

```json
{
  "name": "io_register_iowq_aff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016016,
      "name": "io_register_iowq_aff",
      "external": false,
      "loc": "io_uring/io_uring.c:4222",
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
      "addr": 18446744071587016016,
      "name": "io_register_iowq_aff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int io_register_iowq_aff(struct io_ring_ctx * ctx, void * arg, unsigned int len)
```

```json
{
  "name": "io_register_iowq_aff",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587410720,
      "name": "io_register_iowq_aff",
      "external": false,
      "loc": "io_uring/register.c:269",
      "file": "io_uring/register.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/register.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410720,
      "name": "io_register_iowq_aff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int io_register_iowq_aff(struct io_ring_ctx * ctx, void * arg, unsigned int len)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

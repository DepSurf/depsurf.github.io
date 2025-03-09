# Function: <code>io_wq_put_and_exit</code>

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
void io_wq_put_and_exit(struct io_wq * wq)
```

```json
{
  "name": "io_wq_put_and_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661104,
      "name": "io_wq_put_and_exit",
      "external": true,
      "loc": "fs/io-wq.c:1082",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661104,
      "name": "io_wq_put_and_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void io_wq_put_and_exit(struct io_wq * wq)
```

```json
{
  "name": "io_wq_put_and_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986080,
      "name": "io_wq_put_and_exit",
      "external": true,
      "loc": "fs/io-wq.c:1271",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986080,
      "name": "io_wq_put_and_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
void io_wq_put_and_exit(struct io_wq * wq)
```

```json
{
  "name": "io_wq_put_and_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586036432,
      "name": "io_wq_put_and_exit",
      "external": true,
      "loc": "io_uring/io-wq.c:1297",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036432,
      "name": "io_wq_put_and_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
void io_wq_put_and_exit(struct io_wq * wq)
```

```json
{
  "name": "io_wq_put_and_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872272,
      "name": "io_wq_put_and_exit",
      "external": true,
      "loc": "io_uring/io-wq.c:1290",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/tctx.c:io_uring_clean_tctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872272,
      "name": "io_wq_put_and_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
void io_wq_put_and_exit(struct io_wq * wq)
```

```json
{
  "name": "io_wq_put_and_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587138256,
      "name": "io_wq_put_and_exit",
      "external": true,
      "loc": "io_uring/io-wq.c:1247",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/tctx.c:io_uring_clean_tctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587138256,
      "name": "io_wq_put_and_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void io_wq_put_and_exit(struct io_wq * wq)
```

```json
{
  "name": "io_wq_put_and_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587424384,
      "name": "io_wq_put_and_exit",
      "external": true,
      "loc": "io_uring/io-wq.c:1266",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/tctx.c:io_uring_clean_tctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424384,
      "name": "io_wq_put_and_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void io_wq_put_and_exit(struct io_wq * wq)
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

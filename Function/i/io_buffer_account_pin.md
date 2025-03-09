# Function: <code>io_buffer_account_pin</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```

```json
{
  "name": "io_buffer_account_pin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560096,
      "name": "io_buffer_account_pin",
      "external": false,
      "loc": "fs/io_uring.c:8472",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560096,
      "name": "io_buffer_account_pin",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```

```json
{
  "name": "io_buffer_account_pin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586512,
      "name": "io_buffer_account_pin",
      "external": false,
      "loc": "fs/io_uring.c:8267",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586512,
      "name": "io_buffer_account_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```

```json
{
  "name": "io_buffer_account_pin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_buffer_account_pin",
      "external": false,
      "loc": "fs/io_uring.c:8979",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905760,
      "name": "io_buffer_account_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071592237309,
      "name": "io_buffer_account_pin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```

```json
{
  "name": "io_buffer_account_pin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_buffer_account_pin",
      "external": false,
      "loc": "io_uring/io_uring.c:10280",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976784,
      "name": "io_buffer_account_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
    },
    {
      "addr": 18446744071594117912,
      "name": "io_buffer_account_pin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```

```json
{
  "name": "io_buffer_account_pin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_buffer_account_pin",
      "external": false,
      "loc": "io_uring/rsrc.c:1108",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842816,
      "name": "io_buffer_account_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    },
    {
      "addr": 18446744071596112327,
      "name": "io_buffer_account_pin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```

```json
{
  "name": "io_buffer_account_pin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_buffer_account_pin",
      "external": false,
      "loc": "io_uring/rsrc.c:998",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109664,
      "name": "io_buffer_account_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071596636767,
      "name": "io_buffer_account_pin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```

```json
{
  "name": "io_buffer_account_pin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_buffer_account_pin",
      "external": false,
      "loc": "io_uring/rsrc.c:843",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389152,
      "name": "io_buffer_account_pin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071597544443,
      "name": "io_buffer_account_pin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx * ctx, struct page * * pages, int nr_pages, struct io_mapped_ubuf * imu, struct page * * last_hpage)
```
</details>
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

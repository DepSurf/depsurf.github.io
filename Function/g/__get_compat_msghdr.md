# Function: <code>__get_compat_msghdr</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * umsg, struct sockaddr * * save_addr, compat_uptr_t * ptr, compat_size_t * len)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589735152,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589735152,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * umsg, struct sockaddr * * save_addr, compat_uptr_t * ptr, compat_size_t * len)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589768208,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589768208,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * umsg, struct sockaddr * * save_addr, compat_uptr_t * ptr, compat_size_t * len)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671744,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671744,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * umsg, struct sockaddr * * save_addr, compat_uptr_t * ptr, compat_size_t * len)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590428752,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590428752,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * umsg, struct sockaddr * * save_addr, compat_uptr_t * ptr, compat_size_t * len)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592027952,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592027952,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * msg, struct sockaddr * * save_addr)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593844160,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:__io_compat_recvmsg_copy_hdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593844160,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * msg, struct sockaddr * * save_addr)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594218576,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:__io_compat_recvmsg_copy_hdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594218576,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * msg, struct sockaddr * * save_addr)
```

```json
{
  "name": "__get_compat_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595015952,
      "name": "__get_compat_msghdr",
      "external": true,
      "loc": "net/compat.c:36",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595015952,
      "name": "__get_compat_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __get_compat_msghdr(struct msghdr * kmsg, struct compat_msghdr * umsg, struct sockaddr * * save_addr, compat_uptr_t * ptr, compat_size_t * len)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct compat_msghdr * msg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct compat_msghdr * umsg</code>
</li>
<li>
<b>Param removed. </b>
<code>compat_uptr_t * ptr</code>
</li>
<li>
<b>Param removed. </b>
<code>compat_size_t * len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>copy_from_iter_full_nocache</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583436400,
      "name": "copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:618",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583436400,
      "name": "copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587393089,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:139",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587908978,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:137",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588260019,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:137",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588448126,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:175",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588853487,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589077888,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590036863,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590067919,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:168",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589982271,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590748537,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:185",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592379577,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:194",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594229257,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:210",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594616265,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:225",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595419081,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:227",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596985199,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:227",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502694016,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235395408,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296304784,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278823104,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588684272,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588396256,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589120448,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
  "name": "copy_from_iter_full_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589160272,
      "name": "copy_from_iter_full_nocache",
      "external": false,
      "loc": "include/linux/uio.h:169",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
</ul>

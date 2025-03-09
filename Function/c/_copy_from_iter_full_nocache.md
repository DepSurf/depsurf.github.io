# Function: <code>_copy_from_iter_full_nocache</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583458336,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:664",
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
      "addr": 18446744071583458336,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583638848,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:664",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583638848,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855056,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:794",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855056,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939968,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:838",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939968,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132509,
      "name": "_copy_from_iter_full_nocache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584118528,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584241696,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241696,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584657088,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:860",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584657088,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584768576,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:867",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584768576,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584818368,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:910",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584818368,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1409
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496118136,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496118136,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229442956,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229442956,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290389152,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290389152,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275180910,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275180910,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210432,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210432,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145648,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145648,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194192,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194192,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_full_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298656,
      "name": "_copy_from_iter_full_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:839",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298656,
      "name": "_copy_from_iter_full_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool _copy_from_iter_full_nocache(void * addr, size_t bytes, struct iov_iter * i)
```
</details>
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

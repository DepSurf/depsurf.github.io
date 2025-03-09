# Function: <code>_copy_from_iter_nocache</code>

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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583464480,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:623",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583464480,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583645392,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:623",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645392,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863264,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:739",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863264,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947120,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:783",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947120,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132620,
      "name": "_copy_from_iter_nocache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584123904,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249184,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249184,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584653664,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:805",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653664,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 847
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584771776,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:812",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584771776,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804048,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:851",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804048,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1755
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585227216,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:731",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585227216,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1401
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:783",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127560,
      "name": "_copy_from_iter_nocache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071586072000,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1659
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:643",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596114180,
      "name": "_copy_from_iter_nocache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587049360,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:399",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_events_user.c:user_event_ftrace",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596639386,
      "name": "_copy_from_iter_nocache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587303760,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1254
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:271",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_events_user.c:user_event_ftrace",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548061,
      "name": "_copy_from_iter_nocache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587588144,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1318
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496127184,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496127184,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229449800,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229449800,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290386416,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290386416,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1548
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275185736,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275185736,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217920,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217920,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153136,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153136,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201680,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201680,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "_copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584306208,
      "name": "_copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:784",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584306208,
      "name": "_copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
size_t _copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
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

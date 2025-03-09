# Function: <code>csum_and_copy_from_iter_full</code>

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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437088,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1095",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437088,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1094
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583458928,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1219",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583458928,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583639440,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1221",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583639440,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855648,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1351",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855648,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583940592,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1427",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940592,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1027
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132530,
      "name": "csum_and_copy_from_iter_full.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584119152,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242336,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242336,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1023
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584657712,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1479",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584657712,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777680,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1485",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777680,
      "name": "csum_and_copy_from_iter_full",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584819792,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1743",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819792,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1662
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590689349,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:294",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590748711,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:294",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591097797,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:294",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
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
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592317231,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:302",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592379769,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:302",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592749400,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:302",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
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
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594154063,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:326",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594229449,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:326",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594621616,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:326",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_getfrag"
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
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594541394,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:347",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_generic_getfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594616457,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595013760,
      "name": "csum_and_copy_from_iter_full",
      "external": false,
      "loc": "include/linux/uio.h:347",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_getfrag"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "net/core/skbuff.c:7038",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:skb_do_copy_data_nocache",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776318,
      "name": "csum_and_copy_from_iter_full.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071594369488,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1865
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496119800,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496119800,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229444492,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229444492,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290370384,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290370384,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275182086,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275182086,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 926
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211072,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211072,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1023
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146288,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146288,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1023
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194832,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194832,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1023
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_from_iter_full",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584299296,
      "name": "csum_and_copy_from_iter_full",
      "external": true,
      "loc": "lib/iov_iter.c:1444",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_generic_getfrag",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/ping.c:ping_getfrag",
        "net/ipv4/ping.c:ping_getfrag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584299296,
      "name": "csum_and_copy_from_iter_full",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1053
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```
</details>
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
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool csum_and_copy_from_iter_full(void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
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

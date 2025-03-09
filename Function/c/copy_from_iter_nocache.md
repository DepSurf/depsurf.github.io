# Function: <code>copy_from_iter_nocache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021952,
      "name": "copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:428",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_do_io",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021952,
      "name": "copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
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
size_t copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583316064,
      "name": "copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:389",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_do_io",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316064,
      "name": "copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
size_t copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439120,
      "name": "copy_from_iter_nocache",
      "external": true,
      "loc": "lib/iov_iter.c:599",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439120,
      "name": "copy_from_iter_nocache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 857
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580744705,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:128",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:bpf_tcp_sendmsg"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588180113,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:166",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588506157,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588712149,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589578866,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589588802,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:159",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589647186,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:167",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590401487,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:176",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590748537,
      "name": "copy_from_iter_nocache",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_iter_nocache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591996272,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:185",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592379577,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:185",
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593811024,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:202",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594229257,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:202",
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581743928,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:217",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_events_user.c:user_event_ftrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594185312,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:217",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594616265,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:217",
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581860744,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:219",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_events_user.c:user_event_ftrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594981984,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:219",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595419081,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:219",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:skb_do_copy_data_nocache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596985199,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:219",
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502277524,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235015980,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295774424,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278511778,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588318885,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588031669,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588650709,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
  "name": "copy_from_iter_nocache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588790517,
      "name": "copy_from_iter_nocache",
      "external": false,
      "loc": "include/linux/uio.h:160",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_memcopy_from_iter"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
size_t copy_from_iter_nocache(void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
</ul>

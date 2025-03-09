# Function: <code>sock_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586171648,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:567",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:__sock_create",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_init",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/icmp.c:icmpv6_sk_init",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171648,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586592768,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:568",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_init",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/icmp.c:icmpv6_sk_init",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592768,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586777072,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:594",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_init",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/icmp.c:icmpv6_sk_init",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586777072,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897504,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:592",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897504,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388784,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:597",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_accept",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_close",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_map_fd",
        "net/socket.c:sock_alloc_file",
        "net/socket.c:sock_alloc_file",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388784,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587692727,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:617",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689504,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587826823,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:597",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821808,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588129687,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125008,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588334823,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329776,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589194327,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:623",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_free",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212774,
      "name": "sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589202272,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589192855,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:623",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_free",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625644,
      "name": "sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589200304,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589086375,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:625",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_free",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:pm_nl_exit_net",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591569034,
      "name": "sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589093904,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589803287,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:675",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_free",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:pm_nl_exit_net",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692326,
      "name": "sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589809632,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591321635,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:676",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:pm_nl_exit_net",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594577771,
      "name": "sock_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591328528,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593075299,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:678",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:pm_nl_exit_net",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593083296,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593526811,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:683",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:pm_nl_exit_net",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593535472,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594298235,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:685",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/mptcp/subflow.c:mptcp_subflow_create_socket",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:pm_nl_exit_net",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594308080,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501828656,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501825288,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234610260,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234607796,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295230976,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295226000,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278174966,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278170680,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587941607,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936560,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587654711,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv4/udp_tunnel.c:udp_tunnel_sock_release",
        "net/ipv4/udp_tunnel.c:udp_sock_create4",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit",
        "net/ipv6/ip6_udp_tunnel.c:udp_sock_create6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649664,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588273383,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268336,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sock_release(struct socket * sock)
```

```json
{
  "name": "sock_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588408695,
      "name": "sock_release",
      "external": true,
      "loc": "net/socket.c:608",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sock_create",
        "net/socket.c:sock_create_lite",
        "net/socket.c:sock_alloc_file"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/ipv4/tcp_ipv4.c:tcp_sk_exit",
        "net/ipv4/icmp.c:icmp_sk_exit",
        "net/ipv4/igmp.c:igmp_net_exit",
        "net/ipv6/ndisc.c:ndisc_net_exit",
        "net/ipv6/icmp.c:icmpv6_sk_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_exit",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588403616,
      "name": "sock_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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

# Function: <code>__cgroup_bpf_run_filter_sock_addr</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752320,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:563",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752320,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817088,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:620",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817088,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907440,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:693",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907440,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960592,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960592,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123424,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1040",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123424,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157232,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1064",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157232,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx, u32 * flags)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176848,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1066",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_pre_connect",
        "net/ipv4/udp.c:udp_pre_connect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_pre_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176848,
      "name": "__cgroup_bpf_run_filter_sock_addr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum cgroup_bpf_attach_type atype, void * t_ctx, u32 * flags)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414592,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1096",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_pre_connect",
        "net/ipv4/udp.c:udp_pre_connect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_pre_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414592,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum cgroup_bpf_attach_type atype, void * t_ctx, u32 * flags)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740560,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1248",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740560,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum cgroup_bpf_attach_type atype, void * t_ctx, u32 * flags)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152144,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1462",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152144,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum cgroup_bpf_attach_type atype, void * t_ctx, u32 * flags)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349584,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1462",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349584,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, int * uaddrlen, enum cgroup_bpf_attach_type atype, void * t_ctx, u32 * flags)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516288,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1466",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_pre_connect",
        "net/ipv4/udp.c:udp_pre_connect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_getname",
        "net/ipv4/af_inet.c:inet_bind_sk",
        "net/ipv4/ping.c:ping_pre_connect",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_getname",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind_sk",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_pre_connect",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_pre_connect",
        "net/ipv6/ping.c:ping_v6_pre_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516288,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492310088,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492310088,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226191972,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226191972,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285548992,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285548992,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272434968,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272434968,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929392,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929392,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875456,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875456,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920640,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920640,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980608,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980608,
      "name": "__cgroup_bpf_run_filter_sock_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock * sk, struct sockaddr * uaddr, enum bpf_attach_type type, void * t_ctx)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * uaddrlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, uaddr, atype, t_ctx, flags</code> ➡️ <code>sk, uaddr, uaddrlen, atype, t_ctx, flags</code>
</li>
</ul>
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

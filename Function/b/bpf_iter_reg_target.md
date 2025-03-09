# Function: <code>bpf_iter_reg_target</code>

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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581031376,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:255",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031376,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039200,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:286",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/prog_iter.c:bpf_prog_iter_init",
        "net/core/sock_map.c:bpf_sockmap_iter_init",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039200,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052624,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:286",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/prog_iter.c:bpf_prog_iter_init",
        "net/core/sock_map.c:bpf_sockmap_iter_init",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052624,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277392,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:286",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/prog_iter.c:bpf_prog_iter_init",
        "net/core/sock_map.c:bpf_sockmap_iter_init",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/udp.c:udp_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277392,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571344,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:287",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/prog_iter.c:bpf_prog_iter_init",
        "kernel/bpf/link_iter.c:bpf_link_iter_init",
        "net/core/sock_map.c:bpf_sockmap_iter_init",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/udp.c:udp_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571344,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947728,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:296",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:bpf_ksym_iter_register",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/prog_iter.c:bpf_prog_iter_init",
        "kernel/bpf/link_iter.c:bpf_link_iter_init",
        "kernel/bpf/cgroup_iter.c:bpf_cgroup_iter_init",
        "net/core/sock_map.c:bpf_sockmap_iter_init",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/udp.c:udp_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947728,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135536,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:296",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:bpf_ksym_iter_register",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/prog_iter.c:bpf_prog_iter_init",
        "kernel/bpf/link_iter.c:bpf_link_iter_init",
        "kernel/bpf/cgroup_iter.c:bpf_cgroup_iter_init",
        "net/core/sock_map.c:bpf_sockmap_iter_init",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/udp.c:udp_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135536,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
```

```json
{
  "name": "bpf_iter_reg_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582282784,
      "name": "bpf_iter_reg_target",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:296",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:bpf_ksym_iter_register",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/map_iter.c:bpf_map_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/task_iter.c:task_iter_init",
        "kernel/bpf/prog_iter.c:bpf_prog_iter_init",
        "kernel/bpf/link_iter.c:bpf_link_iter_init",
        "kernel/bpf/cgroup_iter.c:bpf_cgroup_iter_init",
        "net/core/sock_map.c:bpf_sockmap_iter_init",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/udp.c:udp_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/route.c:ip6_route_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282784,
      "name": "bpf_iter_reg_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int bpf_iter_reg_target(const struct bpf_iter_reg * reg_info)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>bpf_iter_get_info</code>

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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032448,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:512",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032448,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040496,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:637",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_show",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "net/core/sock_map.c:sock_hash_seq_show",
        "net/core/sock_map.c:sock_map_seq_show",
        "net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040496,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581053888,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:637",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_vma_seq_stop",
        "kernel/bpf/task_iter.c:task_vma_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_show",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "net/core/sock_map.c:sock_hash_seq_show",
        "net/core/sock_map.c:sock_map_seq_show",
        "net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053888,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:660",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_vma_seq_stop",
        "kernel/bpf/task_iter.c:task_vma_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_show",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "net/core/sock_map.c:sock_hash_seq_show",
        "net/core/sock_map.c:sock_map_seq_show",
        "net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186306,
      "name": "bpf_iter_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581278896,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:659",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_vma_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_show",
        "kernel/bpf/link_iter.c:bpf_link_seq_show",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "net/core/sock_map.c:sock_hash_seq_show",
        "net/core/sock_map.c:sock_map_seq_show",
        "net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960587,
      "name": "bpf_iter_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581573008,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:672",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:bpf_iter_ksym_seq_show",
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_vma_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_show",
        "kernel/bpf/link_iter.c:bpf_link_seq_show",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_stop",
        "net/core/sock_map.c:sock_hash_seq_show",
        "net/core/sock_map.c:sock_map_seq_show",
        "net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596021076,
      "name": "bpf_iter_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581949552,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:672",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:bpf_iter_ksym_seq_show",
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_vma_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_show",
        "kernel/bpf/link_iter.c:bpf_link_seq_show",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_stop",
        "net/core/sock_map.c:sock_hash_seq_show",
        "net/core/sock_map.c:sock_map_seq_show",
        "net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596542689,
      "name": "bpf_iter_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582137360,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
```

```json
{
  "name": "bpf_iter_get_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_get_info",
      "external": true,
      "loc": "kernel/bpf/bpf_iter.c:672",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:bpf_iter_ksym_seq_show",
        "kernel/bpf/map_iter.c:bpf_map_seq_show",
        "kernel/bpf/task_iter.c:task_vma_seq_show",
        "kernel/bpf/task_iter.c:task_file_seq_show",
        "kernel/bpf/task_iter.c:task_seq_show",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_show",
        "kernel/bpf/link_iter.c:bpf_link_seq_show",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_stop",
        "net/core/sock_map.c:sock_hash_seq_show",
        "net/core/sock_map.c:sock_map_seq_show",
        "net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show",
        "net/netlink/af_netlink.c:netlink_seq_stop",
        "net/netlink/af_netlink.c:netlink_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_stop",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_stop",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_stop",
        "net/ipv6/ip6_fib.c:ipv6_route_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597445793,
      "name": "bpf_iter_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582284704,
      "name": "bpf_iter_get_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct bpf_prog * bpf_iter_get_info(struct bpf_iter_meta * meta, bool in_stop)
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

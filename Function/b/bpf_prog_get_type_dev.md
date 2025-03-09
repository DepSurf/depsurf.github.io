# Function: <code>bpf_prog_get_type_dev</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550644,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1100",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:sockmap_get_from_fd"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545456,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580630371,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1201",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630224,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580697625,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1387",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688848,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580769795,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1524",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756304,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580819877,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806560,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580944464,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1923",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928352,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941842,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1897",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925120,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580944322,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1905",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928480,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581148466,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1999",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131664,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581432091,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2245",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403696,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785259,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2279",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754736,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581946425,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2358",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915248,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582072889,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2398",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/tcx.c:tcx_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "drivers/net/netkit.c:netkit_prog_attach",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041120,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492143388,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492122216,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226039072,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226023260,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285350104,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285330080,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272305250,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272293446,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788677,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775360,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580734853,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721536,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580779925,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766608,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```

```json
{
  "name": "bpf_prog_get_type_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838168,
      "name": "bpf_prog_get_type_dev",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/net/tun.c:tun_set_ebpf",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824768,
      "name": "bpf_prog_get_type_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_prog * bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv)
```
</details>
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

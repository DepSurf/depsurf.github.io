# Function: <code>bpf_prog_get_type</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get_type(u32 ufd, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_prog_get_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580421312,
      "name": "bpf_prog_get_type",
      "external": true,
      "loc": "kernel/bpf/syscall.c:712",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421312,
      "name": "bpf_prog_get_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type(u32 ufd, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_prog_get_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580473892,
      "name": "bpf_prog_get_type",
      "external": true,
      "loc": "kernel/bpf/syscall.c:809",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
      "addr": 18446744071580469760,
      "name": "bpf_prog_get_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get_type(u32 ufd, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_prog_get_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580494894,
      "name": "bpf_prog_get_type",
      "external": true,
      "loc": "kernel/bpf/syscall.c:914",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
      "addr": 18446744071580490864,
      "name": "bpf_prog_get_type",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580550644,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:529",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:sockmap_get_from_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580676514,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:529",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587660665,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:529",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587719983,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:529",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636437,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:529",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580630371,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580755813,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807522,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431283,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587988707,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588053743,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588971914,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589016060,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:629",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580697625,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580820725,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580874146,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577011,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588147034,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222047,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589195994,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242957,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:703",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580769795,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915286,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580970178,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586828964,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588466273,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588556163,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589649487,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589697957,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:880",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580819877,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968742,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024306,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586975044,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588671841,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773171,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589873695,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589919413,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580944461,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117074,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131254,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143626,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_bpf_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587800692,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589537089,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589644654,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590902255,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590947451,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1469",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580941842,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132916,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149384,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165334,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183602,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_bpf_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858340,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589546113,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589668334,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590963871,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591009651,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1688",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:fanout_set_data"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580944322,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153106,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166184,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182326,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201970,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_bpf_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587737316,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589443825,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589559486,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590894015,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590944772,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1778",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581148466,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389780,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405256,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422934,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588332516,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178769,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590304462,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591727423,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591780635,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:1904",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581432091,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713673,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729081,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748954,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589724042,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591741136,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591889334,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593429436,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593493017,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2041",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581785259,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582120476,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136649,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582163930,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591342970,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593530544,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593691606,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595344108,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595400781,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2449",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:fanout_set_data"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581946425,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317084,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333817,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360858,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591704506,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593996144,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594172406,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595739628,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595797319,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2625",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:fanout_set_data"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582072889,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478124,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494825,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "kernel/bpf/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582498860,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "kernel/bpf/tcx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/tcx.c:tcx_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582527706,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592370574,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "drivers/net/netkit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/netkit.c:netkit_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592448202,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594780384,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594968953,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596587471,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596647991,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:2796",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:fanout_set_data"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492143384,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492318108,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492376272,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499970436,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502224428,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502338924,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503593044,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503643080,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226039068,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 3226203252,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 3226262096,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3232523036,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 3234970356,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 3235079624,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_parse_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 3236238256,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 3236290624,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285350100,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285557760,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285633548,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293295924,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295711860,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295862060,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297402112,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297468808,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272305250,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272443920,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272469980,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277045814,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278469106,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278561420,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279545978,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279589812,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580788677,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937542,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993154,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586732052,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588278577,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588379555,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589478063,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589523781,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580734853,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883606,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939346,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599268,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587991393,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588092243,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589203055,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249845,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580779925,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928790,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984354,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586929604,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588610401,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588711731,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589914927,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589965045,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
  "name": "bpf_prog_get_type",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580838168,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989334,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045228,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_perf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587037028,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_set_ebpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588748081,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588851987,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589967519,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:parse_nla_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590017630,
      "name": "bpf_prog_get_type",
      "external": false,
      "loc": "include/linux/bpf.h:882",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct bpf_prog * bpf_prog_get_type(u32 ufd, enum bpf_prog_type type)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct bpf_prog * bpf_prog_get_type(u32 ufd, enum bpf_prog_type type)
```
</details>
</li>
</ul>

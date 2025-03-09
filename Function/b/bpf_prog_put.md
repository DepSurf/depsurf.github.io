# Function: <code>bpf_prog_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364640,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:546",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_ioctl",
        "net/core/filter.c:__bpf_prog_release",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364640,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421344,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:636",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_release",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:__bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421344,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580469792,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:699",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_release",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:__bpf_prog_release",
        "net/core/lwt_bpf.c:bpf_lwt_prog_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469792,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580497013,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:787",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_lwt_prog_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490608,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550072,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:948",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:sockmap_get_from_fd",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/sockmap.c:sock_map_prog",
        "kernel/bpf/sockmap.c:sock_map_free",
        "kernel/bpf/sockmap.c:sock_map_free",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:_free_event",
        "drivers/net/tun.c:tun_detach_all",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_lwt_prog_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543728,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580639711,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1047",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/sockmap.c:sock_map_release",
        "kernel/bpf/sockmap.c:sock_map_release",
        "kernel/bpf/sockmap.c:sock_map_release",
        "kernel/bpf/sockmap.c:sock_map_prog",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629808,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580697486,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1233",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688416,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580768139,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1340",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755872,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580820036,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812816,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580949367,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1748",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:_free_event",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945312,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946738,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1722",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:_free_event",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/xen-netfront.c:xennet_xdp",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:dev_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/ipv6/seg6_local.c:destroy_attr_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942432,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580949075,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1725",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "kernel/events/core.c:_free_event",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/xen-netfront.c:xennet_xdp",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/ipv6/seg6_local.c:destroy_attr_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580944912,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581153978,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1813",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "drivers/net/tun.c:tun_xdp",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/ipv6/seg6_local.c:destroy_attr_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149056,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581432241,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2057",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "drivers/net/tun.c:tun_xdp",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd",
        "net/ipv6/seg6_local.c:destroy_attr_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424480,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785409,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2080",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "drivers/net/tun.c:tun_xdp",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd",
        "net/ipv6/seg6_local.c:destroy_attr_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755504,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581946574,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2159",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_get_prog_attach_type",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd",
        "net/ipv6/seg6_local.c:destroy_attr_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916016,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582073029,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2199",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/core.c:bpf_prog_free",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_replace",
        "kernel/bpf/bpf_iter.c:iter_release",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/mprog.c:bpf_mprog_detach",
        "kernel/bpf/mprog.c:bpf_mprog_attach",
        "kernel/bpf/mprog.c:bpf_mprog_attach",
        "kernel/bpf/mprog.c:bpf_mprog_tuple_relative",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog",
        "kernel/bpf/tcx.c:tcx_link_update",
        "kernel/bpf/tcx.c:tcx_link_update",
        "kernel/bpf/tcx.c:tcx_link_update",
        "kernel/bpf/tcx.c:tcx_link_release",
        "kernel/bpf/tcx.c:tcx_link_prog_attach",
        "kernel/bpf/tcx.c:tcx_uninstall",
        "kernel/bpf/tcx.c:tcx_prog_detach",
        "kernel/bpf/tcx.c:tcx_prog_attach",
        "kernel/bpf/tcx.c:tcx_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "drivers/net/netkit.c:netkit_uninit",
        "drivers/net/netkit.c:netkit_link_attach",
        "drivers/net/netkit.c:netkit_link_update",
        "drivers/net/netkit.c:netkit_link_update",
        "drivers/net/netkit.c:netkit_link_update",
        "drivers/net/netkit.c:netkit_link_release",
        "drivers/net/netkit.c:netkit_prog_detach",
        "drivers/net/netkit.c:netkit_prog_attach",
        "drivers/net/netkit.c:netkit_prog_attach",
        "drivers/net/tun.c:tun_xdp",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:bpf_xdp_link_update",
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd",
        "net/ipv6/seg6_local.c:destroy_attr_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041888,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492145792,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492139384,
      "name": "bpf_prog_put",
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226040464,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_lwt_prog_destroy",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226032068,
      "name": "bpf_prog_put",
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285353384,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285340992,
      "name": "bpf_prog_put",
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272305362,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272299532,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788836,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781616,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580735012,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727792,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580780084,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772864,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838327,
      "name": "bpf_prog_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1361",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/bpf/arraymap.c:prog_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_free_event",
        "net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_attach_bpf",
        "net/core/xdp.c:xdp_attachment_setup",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/lwt_bpf.c:bpf_destroy_state",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831088,
      "name": "bpf_prog_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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

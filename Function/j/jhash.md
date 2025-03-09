# Function: <code>jhash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579481923,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383173,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038400,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586710657,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586896264,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583038400,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579495763,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287993,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580446096,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582762922,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331008,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587158369,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342698,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587694149,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758064,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071583331008,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579515962,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580331609,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580500256,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582858202,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455984,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587357359,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545642,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587902901,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582853568,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071583455984,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579504057,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580343785,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580529232,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582935402,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476480,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587259152,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587490303,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587659600,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587691706,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588060031,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588068567,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930240,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071583476480,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071587259152,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071587659600,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071588068567,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579530760,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397222,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580592784,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673456,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583095530,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657440,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587763408,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587778624,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588012623,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184000,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588218459,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588394826,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588598367,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612732,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673456,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071583090464,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071583657440,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071587763408,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071587778624,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071588184000,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071588612732,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579558252,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459017,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580688080,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580747497,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:__sock_hash_lookup_elem",
        "kernel/bpf/sockmap.c:sock_hash_delete_elem",
        "kernel/bpf/sockmap.c:sock_hash_get_next_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866752,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583295415,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583875136,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588363887,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588573047,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754538,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588960775,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866752,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071583293552,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071583875136,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595427,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580514585,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580760115,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582974880,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583413895,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958560,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588229160,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588554191,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710640,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588776663,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588974778,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589186423,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974880,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071583411936,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071583958560,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071588710640,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579616810,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580569593,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580845344,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583155920,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583599575,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138688,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588566274,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588965311,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589209591,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589420778,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589640108,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155920,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584138688,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579644794,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580616745,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580896384,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583261984,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583705735,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584261136,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588783394,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589189775,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589434855,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589645098,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589864316,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261984,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584261136,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579656224,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071580716240,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581034896,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071581108640,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583589056,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583819232,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071584001632,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584073456,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071584669008,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589549056,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589649552,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 18446744071589814528,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590160672,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ]
    },
    {
      "addr": 18446744071590334048,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590378528,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590403440,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590420256,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 18446744071590434496,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590850368,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590888288,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 18446744071590905856,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656224,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580716240,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071581034896,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071581108640,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071583589056,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071583819232,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071584001632,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071584073456,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584669008,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071589549056,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071589649552,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071589814528,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590160672,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071590334048,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590378528,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590403440,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590420256,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071590434496,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590850368,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590888288,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071590905856,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579635696,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071580705680,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581043424,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071581140192,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583709376,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583940608,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071584121440,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584192864,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071584786656,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589558160,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589674112,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 18446744071589850736,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590209696,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ]
    },
    {
      "addr": 18446744071590386784,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590436000,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590461280,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590478560,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 18446744071590492368,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590911152,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590949792,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 18446744071590969456,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635696,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580705680,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071581043424,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071581140192,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071583709376,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071583940608,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071584121440,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071584192864,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584786656,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071589558160,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071589674112,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071589850736,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590209696,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071590386784,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590436000,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590461280,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590478560,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071590492368,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590911152,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071590949792,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071590969456,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579642352,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071580709840,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581057984,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071581157008,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583733952,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583967584,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071584148944,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584219760,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071584830720,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589456112,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589656448,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 18446744071589756112,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590123808,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ]
    },
    {
      "addr": 18446744071590303088,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590361760,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590387104,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590404144,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 18446744071590417856,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590840528,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590879728,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 18446744071590900400,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642352,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071580709840,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071581057984,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071581157008,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071583733952,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071583967584,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071584148944,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071584219760,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071584830720,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071589456112,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071589656448,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071589756112,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590123808,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071590303088,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590361760,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590387104,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590404144,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071590417856,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590840528,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590879728,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071590900400,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579718960,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071580887776,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581282960,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071581394896,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584095312,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584332576,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071584532880,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584605200,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071585249584,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590193552,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590413248,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 18446744071590515264,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590901328,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ]
    },
    {
      "addr": 18446744071591090480,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591153472,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591181280,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591202080,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 18446744071591216448,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591659824,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ioam6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591668784,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591710384,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 18446744071591734032,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718960,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071580887776,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071581282960,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071581394896,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071584095312,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071584332576,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071584532880,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071584605200,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071585249584,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071590193552,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590413248,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071590515264,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071590901328,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071591090480,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071591153472,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071591181280,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071591202080,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071591216448,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071591659824,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071591668784,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071591710384,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071591734032,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579820944,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071581122704,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581578768,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071581615696,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ]
    },
    {
      "addr": 18446744071581641888,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581718272,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582703936,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    },
    {
      "addr": 18446744071584690352,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584953216,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071585172864,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585254256,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071586091472,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591756880,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592010528,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 18446744071592121872,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592540272,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ]
    },
    {
      "addr": 18446744071592741264,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592809968,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592840096,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592862928,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 18446744071592878624,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593354656,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ioam6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593364320,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593410352,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_add",
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 18446744071593436064,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820944,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071581122704,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071581578768,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071581615696,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071581641888,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071581718272,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071582703936,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071584690352,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071584953216,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071585172864,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071585254256,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071586091472,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071591756880,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592010528,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071592121872,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592540272,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071592741264,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592809968,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592840096,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592862928,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071592878624,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071593354656,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071593364320,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071593410352,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071593436064,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579957424,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071581432752,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581957232,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem",
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071581999904,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ]
    },
    {
      "addr": 18446744071582033312,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582124992,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582304768,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583229296,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    },
    {
      "addr": 18446744071585381280,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585665984,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071585900208,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585988128,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071587074784,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593547824,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593825984,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 18446744071593944416,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594398800,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ]
    },
    {
      "addr": 18446744071594612400,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594685616,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594717072,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594740704,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 18446744071594757328,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595261568,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ioam6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595271680,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595320880,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_add",
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 18446744071595351200,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957424,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071581432752,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071581957232,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071581999904,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071582033312,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071582124992,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071582304768,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071583229296,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071585381280,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071585665984,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071585900208,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071585988128,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071587074784,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071593547824,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071593825984,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071593944416,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071594398800,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071594612400,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071594685616,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071594717072,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071594740704,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071594757328,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071595261568,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071595271680,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071595320880,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071595351200,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580007760,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071581529584,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581747888,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:find_user_event"
      ]
    },
    {
      "addr": 18446744071582145360,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_hash"
      ]
    },
    {
      "addr": 18446744071582191280,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bloom_filter.c:hash"
      ]
    },
    {
      "addr": 18446744071582228064,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583448272,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585895792,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071586132016,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586220608,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071587333360,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594200448,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594787072,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_update_congestion_control"
      ]
    },
    {
      "addr": 18446744071595004352,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595109072,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595132752,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595657232,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ioam6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595715904,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_add",
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/handshake/request.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007760,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581529584,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071581747888,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071582145360,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071582191280,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071582228064,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583448272,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071585895792,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071586132016,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071586220608,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071587333360,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071594200448,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071594787072,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071595004352,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071595109072,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071595132752,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071595657232,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071595715904,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047472,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:get_unbound_pool"
      ]
    },
    {
      "addr": 18446744071581641552,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ]
    },
    {
      "addr": 18446744071581864656,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:find_user_event"
      ]
    },
    {
      "addr": 18446744071582294160,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_hash"
      ]
    },
    {
      "addr": 18446744071582340176,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bloom_filter.c:hash"
      ]
    },
    {
      "addr": 18446744071582384016,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583641712,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586144256,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_hash"
      ]
    },
    {
      "addr": 18446744071586381296,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586473168,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:strhash"
      ]
    },
    {
      "addr": 18446744071587616752,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594997728,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595598464,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_update_congestion_control"
      ]
    },
    {
      "addr": 18446744071595817024,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595921744,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595949584,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_check"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596504880,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ioam6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ioam6.c:ioam6_namespace",
        "net/ipv6/ioam6.c:ioam6_genl_ns_set_schema",
        "net/ipv6/ioam6.c:ioam6_genl_delns",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/ioam6.c:ioam6_genl_addns"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596563680,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_cache_add",
        "net/ipv6/calipso.c:calipso_cache_check"
      ]
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/handshake/request.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047472,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581641552,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071581864656,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071582294160,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071582340176,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071582384016,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583641712,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071586144256,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071586381296,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071586473168,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071587616752,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071594997728,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071595598464,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071595817024,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071595921744,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071595949584,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071596504880,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071596563680,
      "name": "jhash.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490815752,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491919692,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492224336,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495499100,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496142416,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502351884,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502807640,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503087808,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503327328,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503584352,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496142416,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224850504,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 3226121268,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228405092,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228867028,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 3229464284,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235090120,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235510772,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235771020,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235999956,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236228996,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228405092,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 3229464284,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283648136,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285014272,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285448040,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289566796,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290400784,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295876284,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296451164,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296796820,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297094244,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297388148,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290400784,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271491150,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272371810,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274681994,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275197858,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278570512,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278923968,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279142230,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279344248,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279539054,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275197858,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579621098,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585545,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580865184,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583230720,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583674471,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229872,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588389778,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588796159,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589039223,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589249466,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589468684,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230720,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584229872,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549466,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532169,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580811312,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583167872,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583611527,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584165072,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586645330,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "drivers/net/vxlan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/vxlan.c:vxlan_fill_metadata_dst",
        "drivers/net/vxlan.c:vxlan_xmit_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588102466,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588508095,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588764263,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588974458,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589193676,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167872,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584165072,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579618378,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576793,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580856432,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583214752,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583658247,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584213632,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588721954,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589232335,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589476087,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589686330,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589905548,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214752,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584213632,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 jhash(const void * key, u32 length, u32 initval)
```

```json
{
  "name": "jhash",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579652042,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633529,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580914800,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_get_next_key",
        "kernel/bpf/hashtab.c:__htab_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583308640,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583756759,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:strhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584318288,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588862354,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589272639,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589522135,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589735658,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:rt6_exception_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589958173,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "jhash",
      "external": false,
      "loc": "include/linux/jhash.h:70",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308640,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071584318288,
      "name": "jhash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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

# Function: <code>__bpf_prog_run_save_cb</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580817666,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:594",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588109207,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:594",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588154253,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:594",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588220945,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:594",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589199602,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:594",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580912486,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588426549,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588475440,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555217,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589653248,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580965782,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588631901,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588680864,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588772129,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589877664,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, struct sk_buff * skb)
```

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123808,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:679",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ]
    },
    {
      "addr": 18446744071589494896,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:679",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap"
      ]
    },
    {
      "addr": 18446744071589546400,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:679",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:run_bpf_filter"
      ]
    },
    {
      "addr": 18446744071589643648,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:679",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590901520,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:679",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123808,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071589494896,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071589546400,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071589643648,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071590901520,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, struct sk_buff * skb)
```

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157648,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:688",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ]
    },
    {
      "addr": 18446744071589497600,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:688",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap"
      ]
    },
    {
      "addr": 18446744071589555424,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:688",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:run_bpf_filter"
      ]
    },
    {
      "addr": 18446744071589667328,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:688",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590962880,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:688",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157648,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071589497600,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071589555424,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071589667328,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071590962880,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581178374,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:731",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589413146,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:731",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589453548,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:731",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:run_bpf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589559696,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:731",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590899949,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:731",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581417713,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:742",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590140394,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:742",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590189436,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:742",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:run_bpf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590304672,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:742",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591733565,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:742",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, const void * ctx)
```

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736400,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:745",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ]
    },
    {
      "addr": 18446744071591675984,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:745",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap"
      ]
    },
    {
      "addr": 18446744071591752224,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:745",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    },
    {
      "addr": 18446744071591888592,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:745",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593426624,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:745",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736400,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071591675984,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071591752224,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071591888592,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071593426624,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, const void * ctx)
```

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148496,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ]
    },
    {
      "addr": 18446744071593476624,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap"
      ]
    },
    {
      "addr": 18446744071593542576,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    },
    {
      "addr": 18446744071593690816,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595340096,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148496,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071593476624,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071593542576,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071593690816,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071595340096,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, const void * ctx)
```

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582345952,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ]
    },
    {
      "addr": 18446744071593942560,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap"
      ]
    },
    {
      "addr": 18446744071594011648,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    },
    {
      "addr": 18446744071594171616,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595735040,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:717",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345952,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071593942560,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071594011648,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071594171616,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071595735040,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, const void * ctx)
```

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512656,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:768",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ]
    },
    {
      "addr": 18446744071594725328,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:768",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_trim_cap"
      ]
    },
    {
      "addr": 18446744071594798016,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:768",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    },
    {
      "addr": 18446744071594968160,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:768",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596582848,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:768",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512656,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071594725328,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071594798016,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071594968160,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071596582848,
      "name": "__bpf_prog_run_save_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492313356,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502222936,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502234400,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502340848,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503597116,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226197492,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234923608,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 3234980328,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3235078252,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236242396,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285552312,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295651344,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295725292,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295859764,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297407656,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272440590,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278431122,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278477182,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278560142,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279550498,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580934582,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588238637,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588287600,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378513,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589482032,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880646,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587951453,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588000416,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091201,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589207024,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580925830,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588570461,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588619424,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710689,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589918896,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
  "name": "__bpf_prog_run_save_cb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580986250,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588707927,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588757234,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850911,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589971520,
      "name": "__bpf_prog_run_save_cb",
      "external": false,
      "loc": "include/linux/filter.h:650",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog * prog, const void * ctx)
```
</details>
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

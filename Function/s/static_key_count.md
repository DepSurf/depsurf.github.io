# Function: <code>static_key_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "static_key_count",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595004174,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527879,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_feat_write",
        "kernel/sched/core.c:sched_feat_write",
        "kernel/sched/core.c:sysctl_numa_balancing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579969293,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:proc_cgroupstats_show",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002366,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154018,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580462211,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580487939,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580508167,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559923,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580797512,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855027,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043143,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "lib/once.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586737429,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109061,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:120",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_encap_enable"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580539282,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:69",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:static_key_disable",
        "kernel/jump_label.c:static_key_enable"
      ],
      "caller_func": [
        "kernel/cgroup.c:proc_cgroupstats_show",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "net/ipv4/udp.c:udp_encap_enable",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537456,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580603314,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:69",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:static_key_disable",
        "kernel/jump_label.c:static_key_enable"
      ],
      "caller_func": [
        "kernel/cgroup.c:proc_cgroupstats_show",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "net/ipv4/udp.c:udp_encap_enable",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601408,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580633170,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:70",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:static_key_disable",
        "kernel/jump_label.c:static_key_enable"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "net/ipv4/udp.c:udp_encap_enable",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631152,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580714580,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:70",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712368,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580847043,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:71",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844768,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915961,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:89",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913520,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581014066,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011440,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581068194,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066816,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581249774,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "mm/page_reporting.c:page_reporting_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247632,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581291854,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "mm/page_reporting.c:page_reporting_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289520,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581309517,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "mm/page_reporting.c:page_reporting_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307360,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581554451,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/syscall.c:__sys_bpf",
        "mm/page_reporting.c:page_reporting_register",
        "lib/once.c:once_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552352,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581906186,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/build_utility.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/syscall.c:__sys_bpf",
        "mm/page_reporting.c:page_reporting_register",
        "lib/once.c:once_deferred",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903536,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582340554,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/build_utility.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/syscall.c:__sys_bpf",
        "mm/page_reporting.c:page_reporting_register",
        "lib/once.c:once_deferred",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337536,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582542764,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/build_utility.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/syscall.c:__sys_bpf",
        "mm/page_reporting.c:page_reporting_register",
        "lib/once.c:once_deferred",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539152,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582711959,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/build_utility.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/syscall.c:__sys_bpf",
        "mm/page_reporting.c:page_reporting_register",
        "lib/once.c:once_deferred",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708304,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492428600,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492427152,
      "name": "static_key_count",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "static_key_count",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224385112,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 3224424640,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm/kernel/ptrace.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3224451448,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:smp_send_stop",
        "arch/arm/kernel/smp.c:smp_send_reschedule",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:tick_broadcast",
        "arch/arm/kernel/smp.c:arch_irq_work_raise",
        "arch/arm/kernel/smp.c:arch_send_call_function_single_ipi",
        "arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask",
        "arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3224460440,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/arm/kernel/swp_emulate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236559304,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/arm/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/fault.c:do_page_fault",
        "arch/arm/mm/fault.c:do_page_fault",
        "arch/arm/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3224528884,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "arch/arm/common/bL_switcher.c:bL_switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 3224622672,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/arm/mach-omap2/pm34xx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224654280,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/arm/mach-omap2/powerdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst",
        "arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 3224712304,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3224731152,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 3224737992,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 3224747872,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 3224763308,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3224799764,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 3224845836,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_delayed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3224873568,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3224895136,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 3224905476,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:tg_cfs_schedulable_down",
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": []
    },
    {
      "addr": 3224955868,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3224959012,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 3224975248,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 3225018584,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 3225038872,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 3225067136,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3225072716,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 3225089340,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_cfs_group_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 3225097132,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch",
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 3225102648,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225106960,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/sched/psi.c:psi_trigger_replace",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225128648,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/power/qos.c:pm_qos_work_fn",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 3225135608,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 3225138776,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225143764,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 3243378912,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225198252,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225222580,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 3225278512,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225329592,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3225339108,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 3225374836,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 3225388224,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225398216,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3225405872,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 3225416548,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 3225470820,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module",
        "kernel/module.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3225527816,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 3225544812,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225549040,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 3225572388,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 3225705844,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 3225714128,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225735988,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ],
      "caller_func": []
    },
    {
      "addr": 3225826780,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 3225942464,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1"
      ],
      "caller_func": []
    },
    {
      "addr": 3226020300,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once"
      ],
      "caller_func": []
    },
    {
      "addr": 3226167160,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:bq_xmit_all"
      ],
      "caller_func": []
    },
    {
      "addr": 3226171788,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 3226195248,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3226207828,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3226311352,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:rseq_ip_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 3226335672,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3226354772,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 3226365860,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 3226391648,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226419488,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 3226450576,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226481584,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:bdi_register_va"
      ],
      "caller_func": []
    },
    {
      "addr": 3226497196,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 3226508612,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 3226538176,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 3226546020,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3226547888,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 3226582152,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226624540,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226679016,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3244024996,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_free_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 3226702632,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226724044,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swapcache_free_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 3226742944,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226796476,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:setup_slub_debug",
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 3226807216,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3243459204,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_bind",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_print_oom_meminfo",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:mem_cgroup_css_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226857132,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 3226873660,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_release",
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226882420,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226901040,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3226950952,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:do_open_execat"
      ],
      "caller_func": []
    },
    {
      "addr": 3226953704,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 3226967320,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 3227050748,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227144772,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3227195700,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227232224,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3227398832,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227541620,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:__set_oom_adj"
      ],
      "caller_func": []
    },
    {
      "addr": 3227579748,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3227653668,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227664656,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 3227703848,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3227719516,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3227727652,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 3227729312,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3227738568,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227750704,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3227802520,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/inode.c:__ext4_journalled_invalidatepage",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3227836696,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format"
      ],
      "caller_func": []
    },
    {
      "addr": 3227866080,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3227927908,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227999256,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 3228098252,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 3228109728,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 3228122008,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 3228143712,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 3229127240,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 3229159040,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ],
      "caller_func": []
    },
    {
      "addr": 3229182456,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_queue_split"
      ],
      "caller_func": []
    },
    {
      "addr": 3229208924,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3229228056,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_request_inserted"
      ],
      "caller_func": []
    },
    {
      "addr": 3229299712,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 3229332728,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pd_init",
        "block/blk-throttle.c:tg_iops_limit",
        "block/blk-throttle.c:tg_bps_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 3229364568,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 3229390060,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 3229471584,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "lib/once.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229516552,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "lib/crc-t10dif.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243553008,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:__gic_init_bases",
        "drivers/irqchip/irq-gic.c:__gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_cpu_if_up",
        "drivers/irqchip/irq-gic.c:gic_handle_irq",
        "drivers/irqchip/irq-gic.c:gic_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243557292,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3230016196,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3230255480,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 3230564264,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3230835600,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/dma/tegra20-apb-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_isr",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_tasklet"
      ],
      "caller_func": []
    },
    {
      "addr": 3230970124,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3231360404,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:add_disk_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:mix_pool_bytes",
        "drivers/char/random.c:__mix_pool_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 3231433620,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_aux_detach_device",
        "drivers/iommu/iommu.c:iommu_aux_attach_device",
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/iommu/iommu.c:__iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3231553520,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231601928,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3231606536,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 3231633504,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 3231637008,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_report_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3231680928,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 3231702924,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 3231961952,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_init",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3231977336,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 3232007272,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 3232026552,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3232147200,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 3232208900,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 3232445328,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ],
      "caller_func": []
    },
    {
      "addr": 3232493156,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232523712,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3232574688,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3232619704,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 3233062584,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 3233074784,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3233091956,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_urb_in_irq",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 3233125836,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 3233145908,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 3233166044,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233183948,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/musb/musb_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_core.c:musb_interrupt",
        "drivers/usb/musb/musb_core.c:musb_writel",
        "drivers/usb/musb/musb_core.c:musb_readl",
        "drivers/usb/musb/musb_core.c:musb_default_writew",
        "drivers/usb/musb/musb_core.c:musb_default_readw",
        "drivers/usb/musb/musb_core.c:musb_default_writeb",
        "drivers/usb/musb/musb_core.c:musb_default_readb"
      ],
      "caller_func": []
    },
    {
      "addr": 3233190136,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/musb/musb_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_trace.c:musb_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 3233199324,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/musb/musb_host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_host.c:musb_urb_dequeue",
        "drivers/usb/musb/musb_host.c:musb_urb_enqueue",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_giveback",
        "drivers/usb/musb/musb_host.c:musb_start_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 3233217964,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/musb/musb_gadget.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_gadget.c:musb_gadget_dequeue",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_queue",
        "drivers/usb/musb/musb_gadget.c:musb_ep_restart",
        "drivers/usb/musb/musb_gadget.c:musb_free_request",
        "drivers/usb/musb/musb_gadget.c:musb_alloc_request",
        "drivers/usb/musb/musb_gadget.c:musb_g_rx",
        "drivers/usb/musb/musb_gadget.c:musb_g_tx",
        "drivers/usb/musb/musb_gadget.c:musb_g_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 3233233280,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/gadget/udc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/gadget/udc/core.c:usb_gadget_giveback_request",
        "drivers/usb/gadget/udc/core.c:usb_gadget_activate",
        "drivers/usb/gadget/udc/core.c:usb_gadget_deactivate",
        "drivers/usb/gadget/udc/core.c:usb_gadget_disconnect",
        "drivers/usb/gadget/udc/core.c:usb_gadget_connect",
        "drivers/usb/gadget/udc/core.c:usb_gadget_vbus_disconnect",
        "drivers/usb/gadget/udc/core.c:usb_gadget_vbus_draw",
        "drivers/usb/gadget/udc/core.c:usb_gadget_vbus_connect",
        "drivers/usb/gadget/udc/core.c:usb_gadget_clear_selfpowered",
        "drivers/usb/gadget/udc/core.c:usb_gadget_set_selfpowered",
        "drivers/usb/gadget/udc/core.c:usb_gadget_wakeup",
        "drivers/usb/gadget/udc/core.c:usb_gadget_frame_number",
        "drivers/usb/gadget/udc/core.c:usb_ep_fifo_flush",
        "drivers/usb/gadget/udc/core.c:usb_ep_fifo_status",
        "drivers/usb/gadget/udc/core.c:usb_ep_set_wedge",
        "drivers/usb/gadget/udc/core.c:usb_ep_clear_halt",
        "drivers/usb/gadget/udc/core.c:usb_ep_set_halt",
        "drivers/usb/gadget/udc/core.c:usb_ep_dequeue",
        "drivers/usb/gadget/udc/core.c:usb_ep_queue",
        "drivers/usb/gadget/udc/core.c:usb_ep_free_request",
        "drivers/usb/gadget/udc/core.c:usb_ep_alloc_request",
        "drivers/usb/gadget/udc/core.c:usb_ep_disable",
        "drivers/usb/gadget/udc/core.c:usb_ep_enable",
        "drivers/usb/gadget/udc/core.c:usb_ep_set_maxpacket_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 3233320604,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3233358264,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233371712,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233487228,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3233495336,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233516628,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3233521864,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/fair_share.c:fair_share_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 3233523784,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3233528488,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power",
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3233530476,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/cpu_cooling.c:cpufreq_power2state",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3233534300,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3233671680,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 3233730000,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3233735752,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 3233789332,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 3233815524,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3233839764,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3234194736,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 3234231800,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor"
      ],
      "caller_func": []
    },
    {
      "addr": 3234333784,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3234503784,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "sound/soc/soc-dapm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/soc-dapm.c:dapm_power_widgets",
        "sound/soc/soc-dapm.c:dapm_power_widgets",
        "sound/soc/soc-dapm.c:dapm_power_widgets",
        "sound/soc/soc-dapm.c:dapm_power_widgets",
        "sound/soc/soc-dapm.c:dapm_seq_check_event",
        "sound/soc/soc-dapm.c:dapm_seq_check_event",
        "sound/soc/soc-dapm.c:snd_soc_dapm_dai_get_connected_widgets",
        "sound/soc/soc-dapm.c:snd_soc_dapm_set_bias_level",
        "sound/soc/soc-dapm.c:snd_soc_dapm_set_bias_level"
      ],
      "caller_func": []
    },
    {
      "addr": 3234517924,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "sound/soc/soc-jack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/soc-jack.c:gpio_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3234622948,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__se_sys_getsockopt",
        "net/socket.c:__se_sys_getsockopt",
        "net/socket.c:__se_sys_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 3234629496,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__release_sock",
        "net/core/sock.c:sk_prot_alloc",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234685728,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234693456,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3234715896,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off"
      ],
      "caller_func": []
    },
    {
      "addr": 3234726156,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 3234790412,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 3234804924,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:netdev_rss_key_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 3234850432,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3234973592,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect_slow",
        "net/core/filter.c:xdp_do_redirect_slow",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 3234980340,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3234986072,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3235009236,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_clean_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 3235014580,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 3235024668,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3235073124,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235078264,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235103956,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 3235161880,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:__qdisc_run"
      ],
      "caller_func": []
    },
    {
      "addr": 3235260380,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_finish",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 3235283292,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe"
      ],
      "caller_func": []
    },
    {
      "addr": 3235321524,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3235352040,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3235367640,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 3235398456,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3235415896,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust",
        "net/ipv4/tcp_input.c:tcp_grow_window",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 3235462408,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_select_window",
        "net/ipv4/tcp_output.c:__tcp_select_window",
        "net/ipv4/tcp_output.c:tcp_small_queue_check",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_options_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3235480380,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3235486868,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3235505720,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3235540432,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 3235566552,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3235614940,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state",
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_dgram_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 3235675812,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3235756044,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3235889716,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_recvmsg",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 3235918840,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3236001752,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3236071396,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 3236094636,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236148832,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 3236167464,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3236182220,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3236222068,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3236242408,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 3236256200,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3236283888,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 3236506984,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:ptr_to_id"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285699456,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "lib/once.c:once_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285695632,
      "name": "static_key_count",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "static_key_count",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271336234,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271344840,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_exit",
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271358956,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/fault.c:do_page_fault",
        "arch/riscv/mm/fault.c:do_page_fault",
        "arch/riscv/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271389712,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271396968,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271406244,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271413586,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271427454,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271453134,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271486574,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_delayed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271512420,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271530718,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271539042,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:tg_cfs_schedulable_down",
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271570148,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271572288,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271583236,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271617052,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271635070,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271656216,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271659210,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271674010,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_task",
        "kernel/sched/debug.c:print_cfs_group_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271681472,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271685804,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/sched/psi.c:psi_trigger_replace",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271701270,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/power/qos.c:pm_qos_work_fn",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271701982,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270630462,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271724866,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271745004,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271785538,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271812430,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279807662,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271836546,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271864626,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271873342,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271880660,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271890202,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271933096,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module",
        "kernel/module.c:module_put",
        "kernel/module.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271976962,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271992208,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271995924,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272017458,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272078750,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272085652,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272102726,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272174800,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272290976,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_user_rnd_init_once"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272413504,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:bq_xmit_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272417996,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272438960,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272447556,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272531570,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272546576,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272556474,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272578162,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272602088,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272627818,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272654474,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272670610,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272677350,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272701536,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272708104,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272709632,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272734972,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272775646,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272820868,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270891036,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_free_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272834436,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272855180,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:swapcache_free_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272873748,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272875650,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272946932,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:setup_slub_debug",
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272956390,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270701980,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_bind",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_print_oom_meminfo",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:mem_cgroup_css_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272999944,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273003556,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273019812,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_release",
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273027554,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273042702,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273083936,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:do_open_execat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273086386,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273101554,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273164750,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273248334,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273290790,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273320836,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273429868,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273478410,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273576660,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:__set_oom_adj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273610842,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273678706,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273687300,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273718132,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273730182,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273736440,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273737728,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273745456,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273754428,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273795556,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/inode.c:__ext4_journalled_invalidatepage",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273820090,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273844500,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273891474,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273941618,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274020236,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274029440,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274039996,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274058982,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274920022,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274945462,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274966810,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_queue_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274988356,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275004986,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_request_inserted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275089540,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pd_init",
        "block/blk-throttle.c:tg_iops_limit",
        "block/blk-throttle.c:tg_bps_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275112324,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275136054,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275204458,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "lib/once.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275245626,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "lib/crc-t10dif.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275482812,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275658448,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275888108,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_unprepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275986094,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276243128,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:add_disk_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:mix_pool_bytes",
        "drivers/char/random.c:__mix_pool_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276402802,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276410864,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276448324,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276465480,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276706086,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276719278,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276744118,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276760982,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276868690,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276920696,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276994442,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277033954,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277065616,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277074740,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277471964,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277482660,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277498530,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277528166,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277543632,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277562420,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277632506,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277646794,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277658310,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277731400,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277739216,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277754308,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277759200,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/fair_share.c:fair_share_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277760722,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277763926,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power",
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277766160,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277868034,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277920972,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277926878,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277964876,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278124818,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278161598,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278182912,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__se_sys_getsockopt",
        "net/socket.c:__se_sys_getsockopt",
        "net/socket.c:__se_sys_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278189580,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__release_sock",
        "net/core/sock.c:sk_prot_alloc",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278236892,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278244310,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278263082,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278271484,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278323922,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278342472,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278375216,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278471812,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278477192,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278482096,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278502696,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_clean_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278507144,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278515940,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278555386,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278560150,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278583346,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278634878,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:__qdisc_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278714550,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278734030,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278764940,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278788454,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278803888,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278826574,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278848790,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_parse_options",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278881300,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_select_window",
        "net/ipv4/tcp_output.c:__tcp_select_window",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_options_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278897194,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278901432,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278919410,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278949436,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278975734,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279013914,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state",
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/af_inet.c:inet_accept",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_dgram_connect",
        "net/ipv4/af_inet.c:__inet_bind",
        "net/ipv4/af_inet.c:inet_bind",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279063304,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279129638,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279253464,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_recvmsg",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279275994,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279346064,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279403596,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279423736,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279467322,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279484130,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279496334,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279531480,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279550506,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279563222,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279591034,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279770836,
      "name": "static_key_count",
      "external": false,
      "loc": "include/linux/jump_label.h:252",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:ptr_to_id"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037042,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035664,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580983122,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981744,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581028242,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026864,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int static_key_count(struct static_key * key)
```

```json
{
  "name": "static_key_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581089602,
      "name": "static_key_count",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "kernel/jump_label.c:__jump_label_update",
        "kernel/jump_label.c:__jump_label_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/clock.c:clear_sched_clock_stable",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088224,
      "name": "static_key_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int static_key_count(struct static_key * key)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int static_key_count(struct static_key * key)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int static_key_count(struct static_key * key)
```
</details>
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

# Function: <code>put_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022480,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:171",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:put_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/cgroup.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/events/core.c:free_event_rcu",
        "kernel/events/core.c:perf_event_alloc",
        "fs/proc/root.c:proc_kill_sb",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022480,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055056,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:171",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055056,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094944,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:190",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094944,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100272,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:193",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100272,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153530,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:186",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153184,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580213533,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:167",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212896,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580265661,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:167",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265328,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580316537,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316192,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580365369,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365024,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438944,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:159",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438944,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580426128,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:151",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426128,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580430560,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:151",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430560,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580594576,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:152",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594576,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580797120,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:152",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797120,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082112,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:152",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082112,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173808,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:155",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173808,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279488,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:156",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/bpf/task_iter.c:fini_seq_pidns",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279488,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491627040,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491627040,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225581324,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225581324,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284619680,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284619680,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272026140,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272026240,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580334169,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333824,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580281433,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281088,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580325417,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325072,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void put_pid_ns(struct pid_namespace * ns)
```

```json
{
  "name": "put_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580380473,
      "name": "put_pid_ns",
      "external": true,
      "loc": "kernel/pid_namespace.c:168",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:put_pid",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:free_event_rcu",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_kill_sb",
        "fs/proc/root.c:proc_fs_context_free",
        "ipc/util.c:sysvipc_proc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380096,
      "name": "put_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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

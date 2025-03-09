# Function: <code>cgroup_is_descendant</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_is_descendant(struct cgroup * cgrp, struct cgroup * ancestor)
```

```json
{
  "name": "cgroup_is_descendant",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579984048,
      "name": "cgroup_is_descendant",
      "external": true,
      "loc": "kernel/cgroup.c:490",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:__conflict_event",
        "arch/x86/events/intel/cqm.c:__conflict_event",
        "kernel/events/core.c:perf_event_aux_ctx",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_task_tick",
        "mm/rmap.c:invalid_page_referenced_vma",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984048,
      "name": "cgroup_is_descendant",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578903656,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:__conflict_event",
        "arch/x86/events/intel/cqm.c:__conflict_event",
        "arch/x86/events/intel/cqm.c:__conflict_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580017925,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580472158,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580838287,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072336,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583212092,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_insert_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586821738,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578903848,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:__conflict_event",
        "arch/x86/events/intel/cqm.c:__conflict_event",
        "arch/x86/events/intel/cqm.c:__conflict_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580051605,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580415628,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580535198,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908847,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147727,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318125,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_insert_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587010159,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:492",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580054845,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:512",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427145,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:512",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580567309,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:512",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954387,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:512",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193474,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:512",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583379905,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:512",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_insert_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136937,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:512",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580083568,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580482892,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580649165,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056083,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323481,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583554877,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_insert_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641612,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580138630,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580566948,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580778545,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194911,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473146,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583775880,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_insert_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949036,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:548",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580185734,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:550",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624596,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:550",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580843265,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:550",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278318,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:550",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567324,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:550",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588097148,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:550",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580231417,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684565,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:563",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939088,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:563",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352875,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:563",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679162,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:563",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588425693,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:563",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580279625,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731589,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992448,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581412379,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751131,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588631053,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580349624,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844706,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151463,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612539,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581975649,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:mem_cgroup_wait_acct_move",
        "mm/memcontrol.c:mem_cgroup_wait_acct_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492634,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580336072,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580835298,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191863,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659840,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582025323,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:mem_cgroup_wait_acct_move",
        "mm/memcontrol.c:mem_cgroup_wait_acct_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589494698,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580340019,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580841141,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210935,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681568,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046294,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589393183,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580494863,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581040949,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451047,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581950848,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352831,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590166390,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:571",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580693641,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:572",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581295034,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:572",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581803502,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:572",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363670,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:572",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_folio_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852451,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:572",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591725470,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:572",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580975534,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:514",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620242,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:514",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582221715,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:514",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866486,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:514",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_folio_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583398955,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:514",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593514782,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:514",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581063496,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:513",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760706,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127597,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:513",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420068,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:513",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083291,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:513",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_folio_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619418,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:513",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593975802,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:513",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581160823,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:511",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877874,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:511",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268720,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:511",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582587540,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:511",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_adjust_freq_unthr_context",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265659,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:511",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_folio_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814362,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:511",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594759402,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:511",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491526964,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492041632,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492350708,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492812116,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493204848,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502177068,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225493532,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 3225938928,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 3226228660,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3226621692,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 3226835512,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 3234922432,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284493204,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285209684,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285589268,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286191912,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286710956,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295649892,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271946690,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272461746,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272773006,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272982648,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278430784,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580248425,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700389,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580961248,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381227,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719867,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588237789,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580195977,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646597,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907376,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324107,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658739,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587950605,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580239673,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580691637,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952496,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581372427,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711179,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588569613,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
  "name": "cgroup_is_descendant",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580292665,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580749141,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016955,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_ctx",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581436319,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:invalid_page_referenced_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778643,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588707069,
      "name": "cgroup_is_descendant",
      "external": false,
      "loc": "include/linux/cgroup.h:565",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
bool cgroup_is_descendant(struct cgroup * cgrp, struct cgroup * ancestor)
```
</details>
</li>
</ul>

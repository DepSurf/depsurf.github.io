# Function: <code>cgroup_taskset_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984272,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup.c:2421",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup_freezer.c:freezer_attach",
        "kernel/cgroup_pids.c:pids_can_attach",
        "kernel/cgroup_pids.c:pids_cancel_attach",
        "kernel/cpuset.c:cpuset_cancel_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984272,
      "name": "cgroup_taskset_first",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011424,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup.c:2462",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup_freezer.c:freezer_attach",
        "kernel/cgroup_pids.c:pids_cancel_attach",
        "kernel/cgroup_pids.c:pids_can_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_cancel_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011424,
      "name": "cgroup_taskset_first",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045008,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup.c:2467",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup_freezer.c:freezer_attach",
        "kernel/cgroup_pids.c:pids_cancel_attach",
        "kernel/cgroup_pids.c:pids_can_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_cancel_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045008,
      "name": "cgroup_taskset_first",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043488,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2027",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043488,
      "name": "cgroup_taskset_first",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092992,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2205",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092992,
      "name": "cgroup_taskset_first",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152080,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152080,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199728,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199728,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246704,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2400",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246704,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294928,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294928,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365648,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2327",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365648,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580352592,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2323",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352592,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580355712,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2336",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355712,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513104,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2391",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513104,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709776,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709776,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983808,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2497",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983808,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071328,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2466",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071328,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168944,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2475",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168944,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491545336,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491545336,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225510072,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225510072,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284516000,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284516000,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271960900,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271960900,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263728,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263728,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211232,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211232,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254976,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254976,
      "name": "cgroup_taskset_first",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_first(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308304,
      "name": "cgroup_taskset_first",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308304,
      "name": "cgroup_taskset_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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

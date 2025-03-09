# Function: <code>cgroup_taskset_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984096,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup.c:2438",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup_freezer.c:freezer_attach",
        "kernel/cgroup_pids.c:pids_can_attach",
        "kernel/cgroup_pids.c:pids_cancel_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984096,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011248,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup.c:2479",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup_freezer.c:freezer_attach",
        "kernel/cgroup_pids.c:pids_cancel_attach",
        "kernel/cgroup_pids.c:pids_can_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "block/blk-cgroup.c:blkcg_can_attach",
        "net/core/netprio_cgroup.c:net_prio_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011248,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044832,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup.c:2484",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup_freezer.c:freezer_attach",
        "kernel/cgroup_pids.c:pids_cancel_attach",
        "kernel/cgroup_pids.c:pids_can_attach",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580044832,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043328,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2044",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580043328,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092832,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2222",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580092832,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580151920,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2240",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580151920,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199568,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2281",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580199568,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246544,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2417",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580246544,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294768,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580294768,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365488,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2344",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580365488,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580352432,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2340",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580352432,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580355552,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2353",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580355552,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580512832,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2408",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/core.c:perf_cgroup_attach",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512832,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709504,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2412",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580709504,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983520,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2514",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580983520,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071040,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2483",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071581071040,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168656,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2492",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071581168656,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491545144,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446603336491545144,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225509908,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 3225509908,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284515808,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 13835058055284515808,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271960712,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446743936271960712,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263568,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580263568,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211072,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580211072,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254816,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580254816,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct task_struct * cgroup_taskset_next(struct cgroup_taskset * tset, struct cgroup_subsys_state * * dst_cssp)
```

```json
{
  "name": "cgroup_taskset_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308144,
      "name": "cgroup_taskset_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/cgroup/cgroup.c:cgroup_taskset_first",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
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
      "addr": 18446744071580308144,
      "name": "cgroup_taskset_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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

# Function: <code>percpu_ref_is_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582791095,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:319",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583036325,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:319",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583068295,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:317",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583328901,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:317",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583175975,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:317",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583453513,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:317",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583231729,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:318",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474297,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:318",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586421090,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:318",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583409025,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:319",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655273,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:319",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586889988,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:319",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583619580,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:325",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583872969,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:325",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200580,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:325",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583724172,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583915709,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958352,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587381236,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580906347,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912396,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584095507,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138480,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587652756,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580959531,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584015532,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218176,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260928,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856852,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581125967,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:350",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:replace_effective_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584407823,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:350",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584615376,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:350",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668256,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:350",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588709268,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:350",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584786160,
      "name": "percpu_ref_is_zero",
      "external": true,
      "loc": "lib/percpu-refcount.c:402",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:replace_effective_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/md/md.c:set_in_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784784,
      "name": "percpu_ref_is_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool percpu_ref_is_zero(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584830224,
      "name": "percpu_ref_is_zero",
      "external": true,
      "loc": "lib/percpu-refcount.c:408",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/md/md.c:set_in_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828816,
      "name": "percpu_ref_is_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool percpu_ref_is_zero(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585248944,
      "name": "percpu_ref_is_zero",
      "external": true,
      "loc": "lib/percpu-refcount.c:408",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/md/md.c:set_in_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247312,
      "name": "percpu_ref_is_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool percpu_ref_is_zero(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586090688,
      "name": "percpu_ref_is_zero",
      "external": true,
      "loc": "lib/percpu-refcount.c:409",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/md/md.c:set_in_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586088928,
      "name": "percpu_ref_is_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool percpu_ref_is_zero(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587073936,
      "name": "percpu_ref_is_zero",
      "external": true,
      "loc": "lib/percpu-refcount.c:410",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/md/md.c:set_in_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071984,
      "name": "percpu_ref_is_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool percpu_ref_is_zero(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587332512,
      "name": "percpu_ref_is_zero",
      "external": true,
      "loc": "lib/percpu-refcount.c:410",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/md/md.c:set_in_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330544,
      "name": "percpu_ref_is_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool percpu_ref_is_zero(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_is_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587615904,
      "name": "percpu_ref_is_zero",
      "external": true,
      "loc": "lib/percpu-refcount.c:410",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_replace",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:mddev_suspend",
        "drivers/md/md.c:mddev_suspend",
        "drivers/md/md.c:mddev_suspend",
        "drivers/md/md.c:mddev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587613904,
      "name": "percpu_ref_is_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492305200,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495845660,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496089424,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496142072,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501061720,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226190368,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 3229193756,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3229417596,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3229463912,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 3233567816,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285543056,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290039760,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290332316,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290400392,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294537248,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272434348,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274975494,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275160606,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275197608,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277808408,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580928331,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583984268,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584186912,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229664,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587487828,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580874395,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583920124,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584122160,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164864,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587255988,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580919579,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583968028,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584170672,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584213424,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587812996,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
  "name": "percpu_ref_is_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580979675,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070038,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "block/blk-mq.c:blk_mq_freeze_queue_wait",
        "block/blk-mq.c:blk_mq_freeze_queue_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275051,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584318064,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587902482,
      "name": "percpu_ref_is_zero",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:334",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:set_in_sync"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool percpu_ref_is_zero(struct percpu_ref * ref)
```
</details>
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

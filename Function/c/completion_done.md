# Function: <code>completion_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646928,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:298",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646928,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662416,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:298",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662416,
      "name": "completion_done",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686672,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:298",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686672,
      "name": "completion_done",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672896,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:301",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672896,
      "name": "completion_done",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703728,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:316",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703728,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579737968,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737968,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579777728,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777728,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579805392,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805392,
      "name": "completion_done",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852960,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852960,
      "name": "completion_done",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892000,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:315",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892000,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579886640,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:315",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886640,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579895824,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:315",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895824,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580010608,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:315",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010608,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149184,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:315",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149184,
      "name": "completion_done",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322880,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:327",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322880,
      "name": "completion_done",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580389872,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:327",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389872,
      "name": "completion_done",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580446000,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:337",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446000,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491047744,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491047744,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225054096,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225054096,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283924784,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283924784,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271644644,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271644644,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579825312,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825312,
      "name": "completion_done",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579759888,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd",
        "drivers/hv/channel_mgmt.c:vmbus_initiate_unload",
        "drivers/hv/channel_mgmt.c:vmbus_initiate_unload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759888,
      "name": "completion_done",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579813328,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813328,
      "name": "completion_done",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool completion_done(struct completion * x)
```

```json
{
  "name": "completion_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858448,
      "name": "completion_done",
      "external": true,
      "loc": "kernel/sched/completion.c:313",
      "file": "kernel/sched/completion.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_is_req_done",
        "drivers/mmc/core/core.c:mmc_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858448,
      "name": "completion_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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

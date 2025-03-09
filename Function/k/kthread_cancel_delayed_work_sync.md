# Function: <code>kthread_cancel_delayed_work_sync</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538384,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1117",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538384,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525328,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1122",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525328,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551200,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1127",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551200,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578640,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1145",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578640,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615648,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1147",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615648,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640720,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640720,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666672,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666672,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702016,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1193",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702016,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680208,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1247",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680208,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686688,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1305",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686688,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765008,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1305",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765008,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870960,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1365",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870960,
      "name": "kthread_cancel_delayed_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013824,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1365",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013824,
      "name": "kthread_cancel_delayed_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067360,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1366",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067360,
      "name": "kthread_cancel_delayed_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110000,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1383",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110000,
      "name": "kthread_cancel_delayed_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490847680,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490847680,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224872604,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224872604,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283680192,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283680192,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271514874,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271514874,
      "name": "kthread_cancel_delayed_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642992,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642992,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571376,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571376,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640256,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640256,
      "name": "kthread_cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```

```json
{
  "name": "kthread_cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674496,
      "name": "kthread_cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1157",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674496,
      "name": "kthread_cancel_delayed_work_sync",
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work * dwork)
```
</details>
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

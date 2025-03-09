# Function: <code>kthread_cancel_work_sync</code>

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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538352,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1102",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538352,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525296,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1107",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525296,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551168,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1112",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551168,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578608,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1130",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578608,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615616,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1132",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615616,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640688,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640688,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666640,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666640,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701984,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1178",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701984,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680176,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1232",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680176,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686656,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1290",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686656,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764976,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1290",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764976,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870928,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1350",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870928,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013776,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1350",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013776,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067312,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1351",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067312,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109952,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1368",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_stop",
        "drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_cancel_sync",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109952,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490847632,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490847632,
      "name": "kthread_cancel_work_sync",
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224872572,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224872572,
      "name": "kthread_cancel_work_sync",
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283680160,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283680160,
      "name": "kthread_cancel_work_sync",
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271514830,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271514830,
      "name": "kthread_cancel_work_sync",
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642960,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642960,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571344,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571344,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640224,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640224,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
```

```json
{
  "name": "kthread_cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674464,
      "name": "kthread_cancel_work_sync",
      "external": true,
      "loc": "kernel/kthread.c:1142",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674464,
      "name": "kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool kthread_cancel_work_sync(struct kthread_work * work)
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

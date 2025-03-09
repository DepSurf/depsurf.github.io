# Function: <code>kthread_destroy_worker</code>

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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539008,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1150",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539008,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525920,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1155",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525920,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551920,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1160",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551920,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580608,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1178",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580608,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618240,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1180",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618240,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644777,
      "name": "kthread_destroy_worker.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579642800,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668256,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668256,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700144,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1226",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700144,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677712,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1280",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677712,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684400,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1338",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684400,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762864,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1338",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762864,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872816,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1398",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872816,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015776,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1398",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_controller_initialize_queue",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015776,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069520,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1403",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_controller_initialize_queue",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069520,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112304,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1420",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_controller_initialize_queue",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112304,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490845880,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490845880,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224873948,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224873948,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283684192,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283684192,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271512708,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271512708,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644576,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644576,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572960,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572960,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641840,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641840,
      "name": "kthread_destroy_worker",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_destroy_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676128,
      "name": "kthread_destroy_worker",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "drivers/ptp/ptp_clock.c:ptp_clock_unregister",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676128,
      "name": "kthread_destroy_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void kthread_destroy_worker(struct kthread_worker * worker)
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

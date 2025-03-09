# Function: <code>kthread_flush_worker</code>

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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537392,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1130",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537392,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524496,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1135",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524496,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550560,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1140",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550560,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577504,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1158",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577504,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615008,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1160",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615008,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639920,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639920,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665872,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665872,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698640,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1206",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_unregister_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698640,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676656,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1260",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676656,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683168,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1318",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683168,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762656,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1318",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762656,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872608,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1378",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872608,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015552,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1378",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015552,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069296,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1379",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069296,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112080,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1396",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112080,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490844176,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490844176,
      "name": "kthread_flush_worker",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224871448,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224871448,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283678864,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283678864,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271511364,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271511364,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642192,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642192,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570592,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570592,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639456,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639456,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void kthread_flush_worker(struct kthread_worker * worker)
```

```json
{
  "name": "kthread_flush_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673728,
      "name": "kthread_flush_worker",
      "external": true,
      "loc": "kernel/kthread.c:1170",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/spi/spi.c:spi_destroy_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673728,
      "name": "kthread_flush_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void kthread_flush_worker(struct kthread_worker * worker)
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

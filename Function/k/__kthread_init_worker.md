# Function: <code>__kthread_init_worker</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539191,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:577",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker"
      ],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536816,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524000,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:582",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524000,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550064,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:589",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550064,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577024,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:607",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577024,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614528,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:609",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614528,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639440,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639440,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665392,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665392,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579700838,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:654",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker"
      ],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "drivers/block/loop.c:loop_configure",
        "drivers/spi/spi.c:spi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697040,
      "name": "__kthread_init_worker",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579678998,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:680",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker"
      ],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675008,
      "name": "__kthread_init_worker",
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579685270,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:707",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker"
      ],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681952,
      "name": "__kthread_init_worker",
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579763562,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:707",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker"
      ],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760560,
      "name": "__kthread_init_worker",
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579868112,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:767",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868112,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009904,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:768",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009904,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063744,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:769",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063744,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106304,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:786",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106304,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490840696,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490840696,
      "name": "__kthread_init_worker",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224870344,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224870344,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283678064,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283678064,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271513614,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271510886,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641712,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641712,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570112,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570112,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638976,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638976,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__kthread_init_worker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672816,
      "name": "__kthread_init_worker",
      "external": true,
      "loc": "kernel/kthread.c:618",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672816,
      "name": "__kthread_init_worker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __kthread_init_worker(struct kthread_worker * worker, const char * name, struct lock_class_key * key)
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

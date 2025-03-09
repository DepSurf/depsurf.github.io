# Function: <code>get_cpu_idle_time_us</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886016,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:490",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886016,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915600,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:582",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915600,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946128,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:580",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946128,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954032,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:590",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954032,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999680,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999680,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051824,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:556",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051824,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098640,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:553",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098640,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143248,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:562",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143248,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190528,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190528,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580258000,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:591",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258000,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580241584,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:639",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241584,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245904,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:640",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245904,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580396592,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:675",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396592,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580615600,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:691",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615600,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580880528,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:691",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580880528,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962864,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:739",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962864,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054720,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:740",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054720,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491419952,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491419952,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225415448,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:get_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225415448,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284366432,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284366432,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271887534,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271887534,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580159328,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159328,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105472,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105472,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150800,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150800,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
u64 get_cpu_idle_time_us(int cpu, u64 * last_update_time)
```

```json
{
  "name": "get_cpu_idle_time_us",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202880,
      "name": "get_cpu_idle_time_us",
      "external": true,
      "loc": "kernel/time/tick-sched.c:566",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202880,
      "name": "get_cpu_idle_time_us",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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

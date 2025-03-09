# Function: <code>jiffies_64_to_clock_t</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807504,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:660",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_times",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807504,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835312,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:667",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_times",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835312,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864368,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:667",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_times",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864368,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872592,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:757",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872592,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916000,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:724",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916000,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960640,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:736",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960640,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007216,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:674",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007216,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050768,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050768,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099824,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099824,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162208,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:652",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162208,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146352,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:652",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146352,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580151040,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:652",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151040,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295568,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:652",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295568,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504320,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:652",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504320,
      "name": "jiffies_64_to_clock_t",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757696,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:652",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757696,
      "name": "jiffies_64_to_clock_t",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840368,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:652",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840368,
      "name": "jiffies_64_to_clock_t",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929760,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:705",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929760,
      "name": "jiffies_64_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491311128,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491311128,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225310048,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225310048,
      "name": "jiffies_64_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284236928,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284236928,
      "name": "jiffies_64_to_clock_t",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271819890,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271819890,
      "name": "jiffies_64_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069024,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069024,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013840,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013840,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060096,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060096,
      "name": "jiffies_64_to_clock_t",
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
u64 jiffies_64_to_clock_t(u64 x)
```

```json
{
  "name": "jiffies_64_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110880,
      "name": "jiffies_64_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times",
        "kernel/trace/trace_clock.c:trace_clock_jiffies",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110880,
      "name": "jiffies_64_to_clock_t",
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

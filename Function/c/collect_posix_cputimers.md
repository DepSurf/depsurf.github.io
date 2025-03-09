# Function: <code>collect_posix_cputimers</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167568,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167568,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232064,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:780",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232064,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216288,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:792",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216288,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221552,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:792",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221552,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369456,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:850",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369456,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580585840,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:857",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585840,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847632,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:857",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847632,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931040,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:858",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931040,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021664,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:858",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021664,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491389088,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491389088,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225386696,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225386696,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284330080,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284330080,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271871818,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271871818,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136768,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136768,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082048,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082048,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127840,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127840,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```

```json
{
  "name": "collect_posix_cputimers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179712,
      "name": "collect_posix_cputimers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:787",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179712,
      "name": "collect_posix_cputimers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void collect_posix_cputimers(struct posix_cputimers * pct, u64 * samples, struct list_head * firing)
```
</details>
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

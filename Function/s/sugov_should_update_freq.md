# Function: <code>sugov_should_update_freq</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717154,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579713436,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:75",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sugov_should_update_freq(struct sugov_policy * sg_policy, u64 time)
```

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743712,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:77",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743712,
      "name": "sugov_should_update_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool sugov_should_update_freq(struct sugov_policy * sg_policy, u64 time)
```

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775616,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:71",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775616,
      "name": "sugov_should_update_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
bool sugov_should_update_freq(struct sugov_policy * sg_policy, u64 time)
```

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818416,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:67",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818416,
      "name": "sugov_should_update_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool sugov_should_update_freq(struct sugov_policy * sg_policy, u64 time)
```

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846928,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846928,
      "name": "sugov_should_update_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579898081,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579941375,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579928397,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:70",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579936689,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:70",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580061374,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:70",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580178026,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:63",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580362730,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:63",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580432538,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:62",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580491734,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:62",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491096660,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225100168,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283985944,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870193,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579805137,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579858353,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_should_update_freq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903633,
      "name": "sugov_should_update_freq",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:69",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool sugov_should_update_freq(struct sugov_policy * sg_policy, u64 time)
```
</details>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
bool sugov_should_update_freq(struct sugov_policy * sg_policy, u64 time)
```
</details>
</li>
</ul>

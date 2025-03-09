# Function: <code>hrtimer_update_softirq_timer</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981616,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1046",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981616,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028416,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1037",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028416,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071296,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1036",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071296,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120832,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120832,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580187631,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580172402,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1077",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580176898,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1077",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580322395,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1188",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580534205,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1188",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790669,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1188",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580873917,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1191",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580958145,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1192",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491341152,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491341152,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225331848,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225331848,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284268640,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284268640,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271838006,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090032,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090032,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035360,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035360,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081104,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081104,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```

```json
{
  "name": "hrtimer_update_softirq_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132608,
      "name": "hrtimer_update_softirq_timer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132608,
      "name": "hrtimer_update_softirq_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hrtimer_update_softirq_timer(struct hrtimer_cpu_base * cpu_base, bool reprogram)
```
</details>
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

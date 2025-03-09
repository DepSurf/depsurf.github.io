# Function: <code>hrtimer_reprogram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579825907,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:606",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579854699,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:596",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579883392,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:596",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
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
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579892355,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:597",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579936923,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:597",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980864,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:764",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980864,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027520,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:755",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027520,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070544,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:754",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070544,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119920,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119920,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180480,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180480,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165408,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:792",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165408,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169984,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:792",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169984,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315216,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:808",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315216,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526176,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:808",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526176,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782064,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:808",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782064,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865088,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:810",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865088,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955760,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:810",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955760,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491340944,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491340944,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225330568,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225330568,
      "name": "hrtimer_reprogram",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284266768,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284266768,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271837050,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271837050,
      "name": "hrtimer_reprogram.constprop.0",
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089120,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089120,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034448,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034448,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080192,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080192,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
```

```json
{
  "name": "hrtimer_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131696,
      "name": "hrtimer_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:775",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131696,
      "name": "hrtimer_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hrtimer_reprogram(struct hrtimer * timer, bool reprogram)
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

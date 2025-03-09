# Function: <code>__hrtimer_start_range_ns</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579982614,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1070",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580030502,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1061",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580073702,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1060",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580122853,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183136,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183136,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167056,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1101",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167056,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172480,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1101",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172480,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317840,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1212",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317840,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529200,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1212",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529200,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580785312,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1212",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785312,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580867536,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1215",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867536,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580958512,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1216",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958512,
      "name": "__hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491341600,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225334532,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284272244,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271838304,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580092053,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580037381,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580083125,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_start_range_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580134805,
      "name": "__hrtimer_start_range_ns",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1084",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode, struct hrtimer_clock_base * base)
```
</details>
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

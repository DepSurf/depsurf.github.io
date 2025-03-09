# Function: <code>hrtimer_force_reprogram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579823867,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:565",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
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
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579852731,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:555",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880288,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:555",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880288,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889824,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:556",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889824,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934336,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:556",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934336,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981376,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:617",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981376,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028032,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:608",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028032,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071056,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:607",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071056,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120432,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120432,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580182816,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182816,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580168021,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:661",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:retrigger_next_event"
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
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580173781,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:661",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:retrigger_next_event"
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
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580318014,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:690",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
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
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580529391,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:690",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
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
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580785503,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:690",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
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
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580867727,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:692",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
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
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580958703,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:692",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491338152,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491338152,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225331548,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225331548,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284267888,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284267888,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271835696,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271835696,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089632,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089632,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034960,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034960,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080704,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080704,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
```

```json
{
  "name": "hrtimer_force_reprogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132208,
      "name": "hrtimer_force_reprogram",
      "external": false,
      "loc": "kernel/time/hrtimer.c:628",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132208,
      "name": "hrtimer_force_reprogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base * cpu_base, int skip_equal)
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

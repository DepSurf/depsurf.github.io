# Function: <code>__tick_nohz_idle_restart_tick</code>

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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053488,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1113",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053488,
      "name": "__tick_nohz_idle_restart_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100320,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1110",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100320,
      "name": "__tick_nohz_idle_restart_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144224,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1135",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144224,
      "name": "__tick_nohz_idle_restart_tick",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580192240,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192240,
      "name": "__tick_nohz_idle_restart_tick",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580259460,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1167",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
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
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580243024,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1208",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
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
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580248000,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1213",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491421072,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491421072,
      "name": "__tick_nohz_idle_restart_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225414848,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225414848,
      "name": "__tick_nohz_idle_restart_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284369536,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284369536,
      "name": "__tick_nohz_idle_restart_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271889552,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271889552,
      "name": "__tick_nohz_idle_restart_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161040,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161040,
      "name": "__tick_nohz_idle_restart_tick",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580110437,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152512,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152512,
      "name": "__tick_nohz_idle_restart_tick",
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "__tick_nohz_idle_restart_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204320,
      "name": "__tick_nohz_idle_restart_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:1142",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204320,
      "name": "__tick_nohz_idle_restart_tick",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
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
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched * ts, ktime_t now)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

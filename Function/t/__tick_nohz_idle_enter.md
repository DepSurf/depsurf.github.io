# Function: <code>__tick_nohz_idle_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __tick_nohz_idle_enter(struct tick_sched * ts)
```

```json
{
  "name": "__tick_nohz_idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887200,
      "name": "__tick_nohz_idle_enter",
      "external": false,
      "loc": "kernel/time/tick-sched.c:785",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_nohz_irq_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887200,
      "name": "__tick_nohz_idle_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 990
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
void __tick_nohz_idle_enter(struct tick_sched * ts)
```

```json
{
  "name": "__tick_nohz_idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916784,
      "name": "__tick_nohz_idle_enter",
      "external": false,
      "loc": "kernel/time/tick-sched.c:906",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_irq_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916784,
      "name": "__tick_nohz_idle_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __tick_nohz_idle_enter(struct tick_sched * ts)
```

```json
{
  "name": "__tick_nohz_idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579947328,
      "name": "__tick_nohz_idle_enter",
      "external": false,
      "loc": "kernel/time/tick-sched.c:904",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_irq_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947328,
      "name": "__tick_nohz_idle_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
void __tick_nohz_idle_enter(struct tick_sched * ts)
```

```json
{
  "name": "__tick_nohz_idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955120,
      "name": "__tick_nohz_idle_enter",
      "external": false,
      "loc": "kernel/time/tick-sched.c:922",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_irq_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955120,
      "name": "__tick_nohz_idle_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1066
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
void __tick_nohz_idle_enter(struct tick_sched * ts)
```

```json
{
  "name": "__tick_nohz_idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000208,
      "name": "__tick_nohz_idle_enter",
      "external": false,
      "loc": "kernel/time/tick-sched.c:914",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_irq_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000208,
      "name": "__tick_nohz_idle_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1089
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void __tick_nohz_idle_enter(struct tick_sched * ts)
```
</details>
</li>
</ul>

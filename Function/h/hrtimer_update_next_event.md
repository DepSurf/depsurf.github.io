# Function: <code>hrtimer_update_next_event</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "hrtimer_update_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580169982,
      "name": "hrtimer_update_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:594",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_interrupt"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166272,
      "name": "hrtimer_update_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "hrtimer_update_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580174510,
      "name": "hrtimer_update_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:594",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_interrupt"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172048,
      "name": "hrtimer_update_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "hrtimer_update_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315952,
      "name": "hrtimer_update_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:594",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315952,
      "name": "hrtimer_update_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "hrtimer_update_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526944,
      "name": "hrtimer_update_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:594",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526944,
      "name": "hrtimer_update_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "hrtimer_update_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782896,
      "name": "hrtimer_update_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:594",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782896,
      "name": "hrtimer_update_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "hrtimer_update_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865936,
      "name": "hrtimer_update_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:596",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865936,
      "name": "hrtimer_update_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "hrtimer_update_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956912,
      "name": "hrtimer_update_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:596",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956912,
      "name": "hrtimer_update_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base * cpu_base)
```
</details>
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

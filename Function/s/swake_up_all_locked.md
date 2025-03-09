# Function: <code>swake_up_all_locked</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891536,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:42",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891536,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886176,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:42",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886176,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895360,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:42",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895360,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010144,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:42",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010144,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580159329,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:complete_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191600,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580335073,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:complete_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382128,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580403297,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:complete_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450816,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swake_up_all_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_all_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580460129,
      "name": "swake_up_all_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:complete_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580510288,
      "name": "swake_up_all_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void swake_up_all_locked(struct swait_queue_head * q)
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

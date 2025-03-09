# Function: <code>update_triggers</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579854458,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:502",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903002,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
u64 update_triggers(struct psi_group * group, u64 now)
```

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944704,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944704,
      "name": "update_triggers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
u64 update_triggers(struct psi_group * group, u64 now)
```

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932960,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:502",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932960,
      "name": "update_triggers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579943738,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:511",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_worker"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580070170,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:522",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_worker"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
u64 update_triggers(struct psi_group * group, u64 now)
```

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:508",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148624,
      "name": "update_triggers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071593880618,
      "name": "update_triggers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
u64 update_triggers(struct psi_group * group, u64 now)
```

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:531",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322208,
      "name": "update_triggers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    },
    {
      "addr": 18446744071595981788,
      "name": "update_triggers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
u64 update_triggers(struct psi_group * group, u64 now, bool * update_total, enum psi_aggregators aggregator)
```

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:437",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_rtpoll_work",
        "kernel/sched/build_utility.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389216,
      "name": "update_triggers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
    },
    {
      "addr": 18446744071596499917,
      "name": "update_triggers.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void update_triggers(struct psi_group * group, u64 now, enum psi_aggregators aggregator)
```

```json
{
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:437",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_rtpoll_work",
        "kernel/sched/build_utility.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474624,
      "name": "update_triggers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    },
    {
      "addr": 18446744071597397962,
      "name": "update_triggers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491102472,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225105456,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283993540,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271684222,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579875114,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579810122,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579863274,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "update_triggers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579908666,
      "name": "update_triggers",
      "external": false,
      "loc": "kernel/sched/psi.c:503",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
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
u64 update_triggers(struct psi_group * group, u64 now)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
u64 update_triggers(struct psi_group * group, u64 now)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
u64 update_triggers(struct psi_group * group, u64 now)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * update_total</code>
</li>
<li>
<b>Param added. </b>
<code>enum psi_aggregators aggregator</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool * update_total</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, now, update_total, aggregator</code> ➡️ <code>group, now, aggregator</code>
</li>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>

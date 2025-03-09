# Function: <code>collect_percpu_times</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853408,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:301",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853408,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901952,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901952,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946496,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946496,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934624,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:301",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934624,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941760,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:310",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941760,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067360,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:321",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067360,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1061
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169904,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:307",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169904,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1143
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580348672,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:332",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580348672,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420384,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:336",
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
      "addr": 18446744071580420384,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580477040,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:336",
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
      "addr": 18446744071580477040,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491101328,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491101328,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225103052,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225103052,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283990016,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283990016,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271682134,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271682134,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874064,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874064,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809072,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809072,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579862224,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862224,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```

```json
{
  "name": "collect_percpu_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907600,
      "name": "collect_percpu_times",
      "external": false,
      "loc": "kernel/sched/psi.c:302",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907600,
      "name": "collect_percpu_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void collect_percpu_times(struct psi_group * group, enum psi_aggregators aggregator, u32 * pchanged_states)
```
</details>
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

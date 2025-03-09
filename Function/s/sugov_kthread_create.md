# Function: <code>sugov_kthread_create</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579715470,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:402",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579712350,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:419",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579744302,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:470",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579777281,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:571",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579819793,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:644",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579847867,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:651",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579896107,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938624,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071579941607,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:679",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926128,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071591290850,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:566",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934640,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071591233930,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:575",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058944,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071592120940,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:575",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164960,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071593884903,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:574",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346288,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
    },
    {
      "addr": 18446744071595982379,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:578",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413520,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
    },
    {
      "addr": 18446744071596500439,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sugov_kthread_create(struct sugov_policy * sg_policy)
```

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:644",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470336,
      "name": "sugov_kthread_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
    },
    {
      "addr": 18446744071597397872,
      "name": "sugov_kthread_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491094308,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225098016,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283983064,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579868219,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579803163,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579856475,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
  "name": "sugov_kthread_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579901659,
      "name": "sugov_kthread_create",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
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
int sugov_kthread_create(struct sugov_policy * sg_policy)
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

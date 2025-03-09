# Function: <code>cpuacct_cpuusage_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579670448,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:99",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:cpuusage_read"
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
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579688930,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:108",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688864,
      "name": "cpuacct_cpuusage_read.isra.4.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713519,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:108",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713456,
      "name": "cpuacct_cpuusage_read.isra.4.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579709872,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:108",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709776,
      "name": "cpuacct_cpuusage_read.isra.4.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579741574,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:109",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741488,
      "name": "cpuacct_cpuusage_read.isra.4.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579774640,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774640,
      "name": "cpuacct_cpuusage_read.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579817440,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817440,
      "name": "cpuacct_cpuusage_read.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579845488,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845488,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893760,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893760,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579936684,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:99",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
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
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579924156,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:99",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
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
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579932540,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:99",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056781,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:95",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055456,
      "name": "cpuacct_cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580164077,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:94",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show",
        "kernel/sched/build_utility.c:cpuusage_read",
        "kernel/sched/build_utility.c:cpuusage_sys_read",
        "kernel/sched/build_utility.c:cpuusage_user_read"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139872,
      "name": "cpuacct_cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580344098,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:94",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show",
        "kernel/sched/build_utility.c:__cpuusage_read"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315040,
      "name": "cpuacct_cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580407533,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:94",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__cpuusage_read"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381552,
      "name": "cpuacct_cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580464061,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:94",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__cpuusage_read"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438752,
      "name": "cpuacct_cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491091280,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491091280,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225094872,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225094872,
      "name": "cpuacct_cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283979360,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283979360,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271679014,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271679014,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579865872,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865872,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579800816,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800816,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579854128,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854128,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuacct_cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899216,
      "name": "cpuacct_cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:98",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/sched/cpuacct.c:__cpuusage_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899216,
      "name": "cpuacct_cpuusage_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct * ca, int cpu, enum cpuacct_stat_index index)
```
</details>
</li>
</ul>

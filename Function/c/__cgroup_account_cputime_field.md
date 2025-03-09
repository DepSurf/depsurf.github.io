# Function: <code>__cgroup_account_cputime_field</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112464,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/stat.c:235",
      "file": "kernel/cgroup/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112464,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172416,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:371",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172416,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220304,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:371",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220304,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269200,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269200,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317360,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317360,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389136,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:368",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389136,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376096,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:367",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376096,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379040,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:378",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379040,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540960,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:378",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540960,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738400,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:383",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738400,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014832,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:419",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:__account_forceidle_time",
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014832,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103248,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:403",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:__account_forceidle_time",
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103248,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581201056,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:450",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:__account_forceidle_time",
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201056,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491572512,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491572512,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225536124,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225536124,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284551488,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284551488,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271984168,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271984168,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286160,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286160,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233552,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233552,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277408,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277408,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331248,
      "name": "__cgroup_account_cputime_field",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:374",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331248,
      "name": "__cgroup_account_cputime_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __cgroup_account_cputime_field(struct cgroup * cgrp, enum cpu_usage_stat index, u64 delta_exec)
```
</details>
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

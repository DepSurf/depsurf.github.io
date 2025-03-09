# Function: <code>cpuacct_account_field</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct * p, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671024,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:263",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_user_time",
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671024,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689664,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:370",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689664,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714272,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:370",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time",
        "kernel/sched/cputime.c:account_user_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714272,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710576,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:370",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579710576,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579742272,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:371",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579742272,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775408,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579775408,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818208,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579818208,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846240,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579846240,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894512,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579894512,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937168,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:361",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579937168,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924640,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:361",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579924640,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933040,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:361",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579933040,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057104,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:346",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071580057104,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177696,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:350",
      "file": "kernel/sched/build_utility.c",
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
      "addr": 18446744071580177696,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580362368,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:350",
      "file": "kernel/sched/build_utility.c",
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
      "addr": 18446744071580362368,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432112,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:350",
      "file": "kernel/sched/build_utility.c",
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
      "addr": 18446744071580432112,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580491312,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:350",
      "file": "kernel/sched/build_utility.c",
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
      "addr": 18446744071580491312,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491092312,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446603336491092312,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225096096,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 3225096096,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283980464,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 13835058055283980464,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271679934,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446743936271679934,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866624,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579866624,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801568,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579801568,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854880,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579854880,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpuacct_account_field(struct task_struct * tsk, int index, u64 val)
```

```json
{
  "name": "cpuacct_account_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900000,
      "name": "cpuacct_account_field",
      "external": true,
      "loc": "kernel/sched/cpuacct.c:360",
      "file": "kernel/sched/cpuacct.c",
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
      "addr": 18446744071579900000,
      "name": "cpuacct_account_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * p</code>
</li>
</ul>
</details>
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

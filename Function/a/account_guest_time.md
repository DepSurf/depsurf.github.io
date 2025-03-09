# Function: <code>account_guest_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579572232,
      "name": "account_guest_time",
      "external": false,
      "loc": "kernel/sched/cputime.c:160",
      "file": "kernel/sched/cputime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_time"
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
  "name": "account_guest_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579583148,
      "name": "account_guest_time",
      "external": false,
      "loc": "kernel/sched/cputime.c:169",
      "file": "kernel/sched/cputime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_time"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579609297,
      "name": "account_guest_time",
      "external": false,
      "loc": "kernel/sched/cputime.c:154",
      "file": "kernel/sched/cputime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_time"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586736,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:142",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586736,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615792,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:142",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615792,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579646208,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:138",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646208,
      "name": "account_guest_time",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683776,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:138",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683776,
      "name": "account_guest_time",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717536,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717536,
      "name": "account_guest_time",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579759968,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759968,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579793584,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793584,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784608,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:140",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784608,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792736,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:140",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792736,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888496,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:140",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888496,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128224,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128224,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580302032,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302032,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369584,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:143",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369584,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425152,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:143",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:vtime_task_switch_generic",
        "kernel/sched/build_policy.c:vtime_guest_exit",
        "kernel/sched/build_policy.c:vtime_account_kernel",
        "kernel/sched/build_policy.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425152,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490937856,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490937856,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224956276,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224956276,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283793856,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283793856,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271570400,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271570400,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735888,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735888,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664688,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:vtime_account_guest",
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664688,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720336,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720336,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void account_guest_time(struct task_struct * p, u64 cputime)
```

```json
{
  "name": "account_guest_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579767696,
      "name": "account_guest_time",
      "external": true,
      "loc": "kernel/sched/cputime.c:139",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_system_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767696,
      "name": "account_guest_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void account_guest_time(struct task_struct * p, u64 cputime)
```
</details>
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

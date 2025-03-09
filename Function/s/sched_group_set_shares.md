# Function: <code>sched_group_set_shares</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626624,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:8219",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626624,
      "name": "sched_group_set_shares",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641200,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:8710",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641200,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665904,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:9331",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665904,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640512,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:9356",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640512,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1621
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670896,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:9825",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670896,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1945
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579704016,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10332",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579704016,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1527
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743248,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10436",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743248,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1606
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773088,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10376",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773088,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815760,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815760,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856480,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:11056",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856480,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848768,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:11170",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848768,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857200,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:11236",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857200,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579964624,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:11638",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964624,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079856,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:11756",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079856,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251328,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:12272",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251328,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316944,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:12590",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316944,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369664,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:13013",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369664,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490997080,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490997080,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225006416,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225006416,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283868752,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283868752,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271607884,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271607884,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791536,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791536,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722320,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722320,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776128,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776128,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "sched_group_set_shares",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824224,
      "name": "sched_group_set_shares",
      "external": true,
      "loc": "kernel/sched/fair.c:10371",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_weight_nice_write_s64",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_shares_write_u64",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824224,
      "name": "sched_group_set_shares",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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

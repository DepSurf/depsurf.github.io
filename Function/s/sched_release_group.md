# Function: <code>sched_release_group</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_release_group(struct task_group * tg)
```

```json
{
  "name": "sched_release_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579826285,
      "name": "sched_release_group",
      "external": true,
      "loc": "kernel/sched/core.c:9794",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_css_released"
      ],
      "caller_func": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884864,
      "name": "sched_release_group",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_release_group(struct task_group * tg)
```

```json
{
  "name": "sched_release_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945693,
      "name": "sched_release_group",
      "external": true,
      "loc": "kernel/sched/core.c:10117",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_css_released"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002208,
      "name": "sched_release_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void sched_release_group(struct task_group * tg)
```

```json
{
  "name": "sched_release_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580102845,
      "name": "sched_release_group",
      "external": true,
      "loc": "kernel/sched/core.c:10297",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_css_released"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164224,
      "name": "sched_release_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void sched_release_group(struct task_group * tg)
```

```json
{
  "name": "sched_release_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161773,
      "name": "sched_release_group",
      "external": true,
      "loc": "kernel/sched/core.c:10441",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_css_released"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212560,
      "name": "sched_release_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void sched_release_group(struct task_group * tg)
```

```json
{
  "name": "sched_release_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580207725,
      "name": "sched_release_group",
      "external": true,
      "loc": "kernel/sched/core.c:10405",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_css_released"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261216,
      "name": "sched_release_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void sched_release_group(struct task_group * tg)
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

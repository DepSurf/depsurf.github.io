# Function: <code>autogroup_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void autogroup_destroy(struct kref * kref)
```

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579650368,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/auto_group.c:27",
      "file": "kernel/sched/auto_group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/auto_group.c:autogroup_move_group",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:sched_autogroup_exit",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650368,
      "name": "autogroup_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void autogroup_destroy(struct kref * kref)
```

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579667768,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/auto_group.c:27",
      "file": "kernel/sched/auto_group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_exit",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665920,
      "name": "autogroup_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void autogroup_destroy(struct kref * kref)
```

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692360,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/auto_group.c:27",
      "file": "kernel/sched/auto_group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_exit",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690496,
      "name": "autogroup_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579688933,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:27",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579719873,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:28",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579752561,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579795425,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579823964,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579872236,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579914490,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579907962,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579916918,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038918,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580209900,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580402572,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580471347,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580531171,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_exit",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_move_group"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491071080,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225075348,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283952684,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271661258,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579844412,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579779324,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579832604,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
  "name": "autogroup_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579877660,
      "name": "autogroup_destroy",
      "external": false,
      "loc": "kernel/sched/autogroup.c:25",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_exit",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_move_group"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void autogroup_destroy(struct kref * kref)
```
</details>
</li>
</ul>

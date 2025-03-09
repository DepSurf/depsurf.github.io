# Function: <code>free_thread_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579368991,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:176",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:free_task"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579387928,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579375417,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:247",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579402266,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:253",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579417964,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:253",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448811,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:258",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470722,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:264",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579496772,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_thread_stack(struct task_struct * tsk)
```

```json
{
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579518544,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:276",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518544,
      "name": "free_thread_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579505790,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:277",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579509241,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:278",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579578373,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:278",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668585,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:341",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579788601,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:340",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579836073,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:338",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579876105,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:336",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void free_thread_stack(struct task_struct * tsk)
```

```json
{
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490621120,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490621120,
      "name": "free_thread_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224707616,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:free_task"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283448208,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:316",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271385048,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:release_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470436,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399368,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470356,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
  "name": "free_thread_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579502130,
      "name": "free_thread_stack",
      "external": false,
      "loc": "kernel/fork.c:273",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:put_task_stack"
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
void free_thread_stack(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void free_thread_stack(struct task_struct * tsk)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void free_thread_stack(struct task_struct * tsk)
```
</details>
</li>
</ul>

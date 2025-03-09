# Function: <code>memcg_charge_kernel_stack</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579452206,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:392",
      "file": "kernel/fork.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470402,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:398",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579496448,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int memcg_charge_kernel_stack(struct task_struct * tsk)
```

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517888,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:411",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517888,
      "name": "memcg_charge_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579505448,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:397",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579508888,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:401",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579577988,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:401",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665059,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:255",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ],
      "caller_func": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664848,
      "name": "memcg_charge_kernel_stack.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784371,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:254",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ],
      "caller_func": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784144,
      "name": "memcg_charge_kernel_stack.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579831139,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:256",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ],
      "caller_func": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830896,
      "name": "memcg_charge_kernel_stack.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579869011,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:254",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ],
      "caller_func": [
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/fork.c:alloc_thread_stack_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868768,
      "name": "memcg_charge_kernel_stack.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490627748,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470112,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399050,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470032,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "memcg_charge_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579501815,
      "name": "memcg_charge_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:407",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
int memcg_charge_kernel_stack(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int memcg_charge_kernel_stack(struct task_struct * tsk)
```
</details>
</li>
</ul>

# Function: <code>alloc_thread_stack_node</code>

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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579370514,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:167",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389315,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:177",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579376711,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:207",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579403529,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:209",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:210",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:207",
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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:209",
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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
long unsigned int * alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516096,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
      "addr": 18446744071579516096,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int * alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497440,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:219",
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
      "addr": 18446744071579497440,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int * alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501232,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:220",
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
      "addr": 18446744071579501232,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int * alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571904,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:220",
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
      "addr": 18446744071579571904,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664992,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:280",
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
      "addr": 18446744071579664992,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784304,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:279",
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
      "addr": 18446744071579784304,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831072,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:277",
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
      "addr": 18446744071579831072,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int alloc_thread_stack_node(struct task_struct * tsk, int node)
```

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868944,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:275",
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
      "addr": 18446744071579868944,
      "name": "alloc_thread_stack_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224707772,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283446656,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:307",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271383930,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
  "name": "alloc_thread_stack_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_thread_stack_node",
      "external": false,
      "loc": "kernel/fork.c:218",
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
long unsigned int * alloc_thread_stack_node(struct task_struct * tsk, int node)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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

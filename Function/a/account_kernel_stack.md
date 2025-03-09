# Function: <code>account_kernel_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void account_kernel_stack(struct thread_info * ti, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359616,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:220",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:free_task",
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359616,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void account_kernel_stack(long unsigned int * stack, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368128,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:221",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:free_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368128,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386352,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:285",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386352,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374160,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:309",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374160,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401024,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:315",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401024,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414192,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:341",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414192,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447328,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:360",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447328,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464032,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:366",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464032,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487296,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487296,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515008,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:379",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515008,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499504,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:382",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499504,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505712,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:383",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505712,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579576400,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:383",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576400,
      "name": "account_kernel_stack.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668920,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:495",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:exit_task_stack_account"
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
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579788968,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:493",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:exit_task_stack_account"
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
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579836433,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:557",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:exit_task_stack_account"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867872,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:537",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:exit_task_stack_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867872,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490618920,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490618920,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224699260,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:free_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224699260,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283436640,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283436640,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271378136,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:release_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271378136,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460960,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460960,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389920,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389920,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460880,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460880,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void account_kernel_stack(struct task_struct * tsk, int account)
```

```json
{
  "name": "account_kernel_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579492592,
      "name": "account_kernel_stack",
      "external": false,
      "loc": "kernel/fork.c:375",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492592,
      "name": "account_kernel_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
<code>long unsigned int * stack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct thread_info * ti</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * stack</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void account_kernel_stack(struct task_struct * tsk, int account)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void account_kernel_stack(struct task_struct * tsk, int account)
```
</details>
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

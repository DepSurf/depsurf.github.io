# Function: <code>rethook_find_ret_addr</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int rethook_find_ret_addr(struct task_struct * tsk, long unsigned int frame, struct llist_node * * cur)
```

```json
{
  "name": "rethook_find_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372064,
      "name": "rethook_find_ret_addr",
      "external": true,
      "loc": "kernel/trace/rethook.c:234",
      "file": "kernel/trace/rethook.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372064,
      "name": "rethook_find_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long unsigned int rethook_find_ret_addr(struct task_struct * tsk, long unsigned int frame, struct llist_node * * cur)
```

```json
{
  "name": "rethook_find_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581708704,
      "name": "rethook_find_ret_addr",
      "external": true,
      "loc": "kernel/trace/rethook.c:236",
      "file": "kernel/trace/rethook.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708704,
      "name": "rethook_find_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long unsigned int rethook_find_ret_addr(struct task_struct * tsk, long unsigned int frame, struct llist_node * * cur)
```

```json
{
  "name": "rethook_find_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855136,
      "name": "rethook_find_ret_addr",
      "external": true,
      "loc": "kernel/trace/rethook.c:249",
      "file": "kernel/trace/rethook.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855136,
      "name": "rethook_find_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long unsigned int rethook_find_ret_addr(struct task_struct * tsk, long unsigned int frame, struct llist_node * * cur)
```

```json
{
  "name": "rethook_find_ret_addr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978016,
      "name": "rethook_find_ret_addr",
      "external": true,
      "loc": "kernel/trace/rethook.c:242",
      "file": "kernel/trace/rethook.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978016,
      "name": "rethook_find_ret_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int rethook_find_ret_addr(struct task_struct * tsk, long unsigned int frame, struct llist_node * * cur)
```
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

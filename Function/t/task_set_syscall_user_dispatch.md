# Function: <code>task_set_syscall_user_dispatch</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int task_set_syscall_user_dispatch(struct task_struct * task, long unsigned int mode, long unsigned int offset, long unsigned int len, char * selector)
```

```json
{
  "name": "task_set_syscall_user_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784288,
      "name": "task_set_syscall_user_dispatch",
      "external": false,
      "loc": "kernel/entry/syscall_user_dispatch.c:72",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch_set_config",
        "kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784288,
      "name": "task_set_syscall_user_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int task_set_syscall_user_dispatch(struct task_struct * task, long unsigned int mode, long unsigned int offset, long unsigned int len, char * selector)
```

```json
{
  "name": "task_set_syscall_user_dispatch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873552,
      "name": "task_set_syscall_user_dispatch",
      "external": false,
      "loc": "kernel/entry/syscall_user_dispatch.c:72",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch_set_config",
        "kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873552,
      "name": "task_set_syscall_user_dispatch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int task_set_syscall_user_dispatch(struct task_struct * task, long unsigned int mode, long unsigned int offset, long unsigned int len, char * selector)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

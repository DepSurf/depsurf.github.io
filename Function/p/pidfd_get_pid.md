# Function: <code>pidfd_get_pid</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579524034,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579555562,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1477",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668192,
      "name": "pidfd_get_pid",
      "external": true,
      "loc": "kernel/pid.c:523",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "mm/madvise.c:__do_sys_process_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668192,
      "name": "pidfd_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675008,
      "name": "pidfd_get_pid",
      "external": true,
      "loc": "kernel/pid.c:523",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "mm/madvise.c:__do_sys_process_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675008,
      "name": "pidfd_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752656,
      "name": "pidfd_get_pid",
      "external": true,
      "loc": "kernel/pid.c:523",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/madvise.c:__do_sys_process_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752656,
      "name": "pidfd_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857488,
      "name": "pidfd_get_pid",
      "external": true,
      "loc": "kernel/pid.c:523",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/pid.c:pidfd_get_task",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857488,
      "name": "pidfd_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998624,
      "name": "pidfd_get_pid",
      "external": true,
      "loc": "kernel/pid.c:524",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/pid.c:pidfd_get_task",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998624,
      "name": "pidfd_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053120,
      "name": "pidfd_get_pid",
      "external": true,
      "loc": "kernel/pid.c:527",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/pid.c:pidfd_get_task",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053120,
      "name": "pidfd_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```

```json
{
  "name": "pidfd_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095584,
      "name": "pidfd_get_pid",
      "external": true,
      "loc": "kernel/pid.c:527",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_waitid_prepare",
        "kernel/pid.c:pidfd_get_task",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095584,
      "name": "pidfd_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490663020,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224738908,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283487408,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271406782,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579497698,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579426578,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579497618,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
  "name": "pidfd_get_pid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579530226,
      "name": "pidfd_get_pid",
      "external": false,
      "loc": "kernel/exit.c:1473",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:kernel_waitid"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct pid * pidfd_get_pid(unsigned int fd, unsigned int * flags)
```
</details>
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

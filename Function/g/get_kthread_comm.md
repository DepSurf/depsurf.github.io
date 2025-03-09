# Function: <code>get_kthread_comm</code>

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
void get_kthread_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "get_kthread_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872912,
      "name": "get_kthread_comm",
      "external": true,
      "loc": "kernel/kthread.c:98",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_task_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872912,
      "name": "get_kthread_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void get_kthread_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "get_kthread_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015888,
      "name": "get_kthread_comm",
      "external": true,
      "loc": "kernel/kthread.c:98",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_task_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015888,
      "name": "get_kthread_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void get_kthread_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "get_kthread_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069648,
      "name": "get_kthread_comm",
      "external": true,
      "loc": "kernel/kthread.c:99",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_task_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069648,
      "name": "get_kthread_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void get_kthread_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "get_kthread_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112432,
      "name": "get_kthread_comm",
      "external": true,
      "loc": "kernel/kthread.c:99",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_task_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112432,
      "name": "get_kthread_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void get_kthread_comm(char * buf, size_t buf_size, struct task_struct * tsk)
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

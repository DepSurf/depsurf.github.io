# Function: <code>__audit_filter_op</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __audit_filter_op(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list, struct audit_names * name, long unsigned int op)
```

```json
{
  "name": "__audit_filter_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_filter_op",
      "external": false,
      "loc": "kernel/auditsc.c:829",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132080,
      "name": "__audit_filter_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071596000727,
      "name": "__audit_filter_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __audit_filter_op(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list, struct audit_names * name, long unsigned int op)
```

```json
{
  "name": "__audit_filter_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_filter_op",
      "external": false,
      "loc": "kernel/auditsc.c:830",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222192,
      "name": "__audit_filter_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071596519220,
      "name": "__audit_filter_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __audit_filter_op(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list, struct audit_names * name, long unsigned int op)
```

```json
{
  "name": "__audit_filter_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__audit_filter_op",
      "external": false,
      "loc": "kernel/auditsc.c:827",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328416,
      "name": "__audit_filter_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071597419658,
      "name": "__audit_filter_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __audit_filter_op(struct task_struct * tsk, struct audit_context * ctx, struct list_head * list, struct audit_names * name, long unsigned int op)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

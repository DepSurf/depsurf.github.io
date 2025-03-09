# Function: <code>task_ptrace</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_ptrace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584318746,
      "name": "task_ptrace",
      "external": false,
      "loc": "security/landlock/ptrace.c:69",
      "file": "security/landlock/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_access_check",
        "security/landlock/ptrace.c:hook_ptrace_access_check"
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
  "name": "task_ptrace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584705802,
      "name": "task_ptrace",
      "external": false,
      "loc": "security/landlock/ptrace.c:69",
      "file": "security/landlock/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_access_check",
        "security/landlock/ptrace.c:hook_ptrace_access_check"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int task_ptrace(const const struct task_struct * parent, const const struct task_struct * child)
```

```json
{
  "name": "task_ptrace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585370272,
      "name": "task_ptrace",
      "external": false,
      "loc": "security/landlock/ptrace.c:64",
      "file": "security/landlock/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_access_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585370272,
      "name": "task_ptrace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int task_ptrace(const const struct task_struct * parent, const const struct task_struct * child)
```

```json
{
  "name": "task_ptrace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586121216,
      "name": "task_ptrace",
      "external": false,
      "loc": "security/landlock/ptrace.c:64",
      "file": "security/landlock/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_access_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586121216,
      "name": "task_ptrace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int task_ptrace(const const struct task_struct * parent, const const struct task_struct * child)
```

```json
{
  "name": "task_ptrace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586359968,
      "name": "task_ptrace",
      "external": false,
      "loc": "security/landlock/ptrace.c:64",
      "file": "security/landlock/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_access_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586359968,
      "name": "task_ptrace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int task_ptrace(const const struct task_struct * parent, const const struct task_struct * child)
```

```json
{
  "name": "task_ptrace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586628736,
      "name": "task_ptrace",
      "external": false,
      "loc": "security/landlock/ptrace.c:64",
      "file": "security/landlock/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ptrace.c:hook_ptrace_traceme",
        "security/landlock/ptrace.c:hook_ptrace_access_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586628736,
      "name": "task_ptrace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int task_ptrace(const const struct task_struct * parent, const const struct task_struct * child)
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

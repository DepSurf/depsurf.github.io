# Function: <code>current_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int current_has_perm(const struct task_struct * tsk, u32 perms)
```

```json
{
  "name": "current_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261760,
      "name": "current_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1571",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_task_movememory",
        "security/selinux/hooks.c:selinux_task_getscheduler",
        "security/selinux/hooks.c:selinux_task_getsid",
        "security/selinux/hooks.c:selinux_task_getpgid",
        "security/selinux/hooks.c:selinux_task_setpgid",
        "security/selinux/hooks.c:selinux_task_create",
        "security/selinux/hooks.c:selinux_capget",
        "security/selinux/hooks.c:selinux_task_kill",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261760,
      "name": "current_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int current_has_perm(const struct task_struct * tsk, u32 perms)
```

```json
{
  "name": "current_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582479840,
      "name": "current_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1642",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_task_kill",
        "security/selinux/hooks.c:selinux_task_movememory",
        "security/selinux/hooks.c:selinux_task_getscheduler",
        "security/selinux/hooks.c:selinux_task_getsid",
        "security/selinux/hooks.c:selinux_task_getpgid",
        "security/selinux/hooks.c:selinux_task_setpgid",
        "security/selinux/hooks.c:selinux_task_create",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:selinux_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479840,
      "name": "current_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int current_has_perm(const struct task_struct * tsk, u32 perms)
```

```json
{
  "name": "current_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582572528,
      "name": "current_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1650",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_task_kill",
        "security/selinux/hooks.c:selinux_task_movememory",
        "security/selinux/hooks.c:selinux_task_getscheduler",
        "security/selinux/hooks.c:selinux_task_getsid",
        "security/selinux/hooks.c:selinux_task_getpgid",
        "security/selinux/hooks.c:selinux_task_setpgid",
        "security/selinux/hooks.c:selinux_task_create",
        "security/selinux/hooks.c:selinux_file_mprotect",
        "security/selinux/hooks.c:selinux_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572528,
      "name": "current_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int current_has_perm(const struct task_struct * tsk, u32 perms)
```
</details>
</li>
</ul>

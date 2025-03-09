# Function: <code>task_has_security</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int task_has_security(struct task_struct * tsk, u32 perms)
```

```json
{
  "name": "task_has_security",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294352,
      "name": "task_has_security",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:81",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_open_policy",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294352,
      "name": "task_has_security",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int task_has_security(struct task_struct * tsk, u32 perms)
```

```json
{
  "name": "task_has_security",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514848,
      "name": "task_has_security",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:81",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_open_policy",
        "security/selinux/selinuxfs.c:sel_write_enforce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514848,
      "name": "task_has_security",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int task_has_security(struct task_struct * tsk, u32 perms)
```

```json
{
  "name": "task_has_security",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607648,
      "name": "task_has_security",
      "external": false,
      "loc": "security/selinux/selinuxfs.c:81",
      "file": "security/selinux/selinuxfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_read_policy",
        "security/selinux/selinuxfs.c:sel_open_policy",
        "security/selinux/selinuxfs.c:sel_write_enforce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607648,
      "name": "task_has_security",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int task_has_security(struct task_struct * tsk, u32 perms)
```
</details>
</li>
</ul>

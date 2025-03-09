# Function: <code>seq_escape_mem</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void seq_escape_mem(struct seq_file * m, const char * src, size_t len, unsigned int flags, const char * esc)
```

```json
{
  "name": "seq_escape_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657440,
      "name": "seq_escape_mem",
      "external": true,
      "loc": "fs/seq_file.c:374",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_escape",
        "fs/proc/array.c:proc_task_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657440,
      "name": "seq_escape_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void seq_escape_mem(struct seq_file * m, const char * src, size_t len, unsigned int flags, const char * esc)
```

```json
{
  "name": "seq_escape_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197472,
      "name": "seq_escape_mem",
      "external": true,
      "loc": "fs/seq_file.c:374",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc/array.c:proc_task_name",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/hooks.c:show_sid",
        "lib/dynamic_debug.c:ddebug_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197472,
      "name": "seq_escape_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void seq_escape_mem(struct seq_file * m, const char * src, size_t len, unsigned int flags, const char * esc)
```

```json
{
  "name": "seq_escape_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773552,
      "name": "seq_escape_mem",
      "external": true,
      "loc": "fs/seq_file.c:374",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc/array.c:proc_task_name",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/hooks.c:show_sid",
        "lib/dynamic_debug.c:ddebug_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773552,
      "name": "seq_escape_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void seq_escape_mem(struct seq_file * m, const char * src, size_t len, unsigned int flags, const char * esc)
```

```json
{
  "name": "seq_escape_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990720,
      "name": "seq_escape_mem",
      "external": true,
      "loc": "fs/seq_file.c:374",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc/array.c:proc_task_name",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/hooks.c:show_sid",
        "lib/dynamic_debug.c:ddebug_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990720,
      "name": "seq_escape_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void seq_escape_mem(struct seq_file * m, const char * src, size_t len, unsigned int flags, const char * esc)
```

```json
{
  "name": "seq_escape_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203344,
      "name": "seq_escape_mem",
      "external": true,
      "loc": "fs/seq_file.c:374",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "fs/proc_namespace.c:show_vfsstat",
        "fs/proc_namespace.c:show_mountinfo",
        "fs/proc_namespace.c:show_vfsmnt",
        "fs/proc/array.c:proc_task_name",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/hooks.c:show_sid",
        "lib/dynamic_debug.c:ddebug_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203344,
      "name": "seq_escape_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void seq_escape_mem(struct seq_file * m, const char * src, size_t len, unsigned int flags, const char * esc)
```
</details>
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

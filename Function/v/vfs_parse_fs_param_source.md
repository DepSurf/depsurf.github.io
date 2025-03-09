# Function: <code>vfs_parse_fs_param_source</code>

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
int vfs_parse_fs_param_source(struct fs_context * fc, struct fs_parameter * param)
```

```json
{
  "name": "vfs_parse_fs_param_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582748720,
      "name": "vfs_parse_fs_param_source",
      "external": true,
      "loc": "fs/fs_context.c:94",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "fs/fs_context.c:legacy_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582748720,
      "name": "vfs_parse_fs_param_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int vfs_parse_fs_param_source(struct fs_context * fc, struct fs_parameter * param)
```

```json
{
  "name": "vfs_parse_fs_param_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296096,
      "name": "vfs_parse_fs_param_source",
      "external": true,
      "loc": "fs/fs_context.c:94",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/ramfs/inode.c:ramfs_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296096,
      "name": "vfs_parse_fs_param_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int vfs_parse_fs_param_source(struct fs_context * fc, struct fs_parameter * param)
```

```json
{
  "name": "vfs_parse_fs_param_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880832,
      "name": "vfs_parse_fs_param_source",
      "external": true,
      "loc": "fs/fs_context.c:94",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/ramfs/inode.c:ramfs_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880832,
      "name": "vfs_parse_fs_param_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int vfs_parse_fs_param_source(struct fs_context * fc, struct fs_parameter * param)
```

```json
{
  "name": "vfs_parse_fs_param_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102480,
      "name": "vfs_parse_fs_param_source",
      "external": true,
      "loc": "fs/fs_context.c:94",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/ramfs/inode.c:ramfs_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102480,
      "name": "vfs_parse_fs_param_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int vfs_parse_fs_param_source(struct fs_context * fc, struct fs_parameter * param)
```

```json
{
  "name": "vfs_parse_fs_param_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584318624,
      "name": "vfs_parse_fs_param_source",
      "external": true,
      "loc": "fs/fs_context.c:94",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/ramfs/inode.c:ramfs_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318624,
      "name": "vfs_parse_fs_param_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int vfs_parse_fs_param_source(struct fs_context * fc, struct fs_parameter * param)
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

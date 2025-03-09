# Function: <code>kernfs_find_and_get_node_by_id</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839152,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:709",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839152,
      "name": "kernfs_find_and_get_node_by_id",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911904,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:708",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911904,
      "name": "kernfs_find_and_get_node_by_id",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939344,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:708",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939344,
      "name": "kernfs_find_and_get_node_by_id",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583274464,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:667",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583274464,
      "name": "kernfs_find_and_get_node_by_id",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583778400,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:675",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583778400,
      "name": "kernfs_find_and_get_node_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584396640,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:696",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584396640,
      "name": "kernfs_find_and_get_node_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625072,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:695",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625072,
      "name": "kernfs_find_and_get_node_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```

```json
{
  "name": "kernfs_find_and_get_node_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584857600,
      "name": "kernfs_find_and_get_node_by_id",
      "external": true,
      "loc": "fs/kernfs/dir.c:711",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584857600,
      "name": "kernfs_find_and_get_node_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct kernfs_node * kernfs_find_and_get_node_by_id(struct kernfs_root * root, u64 id)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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

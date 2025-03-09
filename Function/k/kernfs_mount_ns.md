# Function: <code>kernfs_mount_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```

```json
{
  "name": "kernfs_mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581501168,
      "name": "kernfs_mount_ns",
      "external": true,
      "loc": "fs/kernfs/mount.c:216",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_mount",
        "fs/sysfs/mount.c:sysfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501168,
      "name": "kernfs_mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```

```json
{
  "name": "kernfs_mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686688,
      "name": "kernfs_mount_ns",
      "external": true,
      "loc": "fs/kernfs/mount.c:231",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_mount",
        "fs/sysfs/mount.c:sysfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686688,
      "name": "kernfs_mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```

```json
{
  "name": "kernfs_mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774896,
      "name": "kernfs_mount_ns",
      "external": true,
      "loc": "fs/kernfs/mount.c:232",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/cgroup.c:cgroup_mount",
        "fs/sysfs/mount.c:sysfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774896,
      "name": "kernfs_mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```

```json
{
  "name": "kernfs_mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829248,
      "name": "kernfs_mount_ns",
      "external": true,
      "loc": "fs/kernfs/mount.c:232",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "fs/sysfs/mount.c:sysfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829248,
      "name": "kernfs_mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```

```json
{
  "name": "kernfs_mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978880,
      "name": "kernfs_mount_ns",
      "external": true,
      "loc": "fs/kernfs/mount.c:305",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "fs/sysfs/mount.c:sysfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978880,
      "name": "kernfs_mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```

```json
{
  "name": "kernfs_mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166288,
      "name": "kernfs_mount_ns",
      "external": true,
      "loc": "fs/kernfs/mount.c:305",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "fs/sysfs/mount.c:sysfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166288,
      "name": "kernfs_mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```

```json
{
  "name": "kernfs_mount_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261360,
      "name": "kernfs_mount_ns",
      "external": true,
      "loc": "fs/kernfs/mount.c:312",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "fs/sysfs/mount.c:sysfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261360,
      "name": "kernfs_mount_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
    }
  ]
}
```
</details>
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct dentry * kernfs_mount_ns(struct file_system_type * fs_type, int flags, struct kernfs_root * root, long unsigned int magic, bool * new_sb_created, const void * ns)
```
</details>
</li>
</ul>

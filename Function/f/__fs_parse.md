# Function: <code>__fs_parse</code>

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
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350832,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350832,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582402624,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582402624,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429856,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429856,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592231486,
      "name": "__fs_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582752608,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/squashfs/super.c:squashfs_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594011474,
      "name": "__fs_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583300256,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/squashfs/super.c:squashfs_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596051901,
      "name": "__fs_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583885296,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/squashfs/super.c:squashfs_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596574433,
      "name": "__fs_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584107088,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "__fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:103",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/squashfs/super.c:squashfs_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/efivarfs/super.c:efivarfs_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597479116,
      "name": "__fs_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584323344,
      "name": "__fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int __fs_parse(struct p_log * log, const struct fs_parameter_spec * desc, struct fs_parameter * param, struct fs_parse_result * result)
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

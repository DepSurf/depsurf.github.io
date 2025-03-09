# Function: <code>fs_parse</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036144,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param",
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036144,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582113920,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
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
      "addr": 18446744071582113920,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579236947,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580347523,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397041,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024019,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382125,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582753441,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583365875,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583368541,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583550094,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583768599,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583905335,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579229763,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333747,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580384289,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030227,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425549,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582825889,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481859,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583484525,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583661038,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583888279,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584024567,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231843,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336691,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580387201,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041475,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447069,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854545,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583504003,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583505981,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682081,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914711,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584053111,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
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
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579270627,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491411,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549345,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264525,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581700685,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187681,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583846979,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/squashfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/super.c:squashfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858963,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583860685,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584041089,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584278039,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584424727,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579323475,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580686499,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580747809,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555181,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582077205,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682193,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584252639,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584415923,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/squashfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/super.c:squashfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584429581,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431685,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584629901,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584905175,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054055,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579397669,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958355,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025041,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927373,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552053,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291057,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584900093,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074264,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/squashfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/super.c:squashfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585091005,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585093269,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310061,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585613431,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774007,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579408597,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045747,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113377,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110189,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757415,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520897,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585128847,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585303736,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/squashfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/super.c:squashfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585320509,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585322773,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585539965,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585844455,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586005527,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579428197,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142787,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581211329,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582250127,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931751,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584751777,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:proc_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585360847,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585537704,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/squashfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/super.c:squashfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585555245,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585557493,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777021,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585852883,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095319,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586251559,
      "name": "fs_parse",
      "external": false,
      "loc": "include/linux/fs_parser.h:68",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493654760,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446603336493654760,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227188556,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup2_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "fs/proc/root.c:proc_parse_param",
        "fs/ramfs/inode.c:ramfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227188556,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287250464,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 13835058055287250464,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273285156,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446743936273285156,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082656,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
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
      "addr": 18446744071582082656,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582020176,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
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
      "addr": 18446744071582020176,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073936,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
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
      "addr": 18446744071582073936,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```

```json
{
  "name": "fs_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145696,
      "name": "fs_parse",
      "external": true,
      "loc": "fs/fs_parser.c:79",
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
      "addr": 18446744071582145696,
      "name": "fs_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int fs_parse(struct fs_context * fc, const struct fs_parameter_description * desc, struct fs_parameter * param, struct fs_parse_result * result)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

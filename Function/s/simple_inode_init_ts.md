# Function: <code>simple_inode_init_ts</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 simple_inode_init_ts(struct inode * inode)
```

```json
{
  "name": "simple_inode_init_ts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584232501,
      "name": "simple_inode_init_ts",
      "external": true,
      "loc": "fs/libfs.c:1967",
      "file": "fs/libfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/libfs.c:alloc_anon_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:__shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/bad_inode.c:iget_failed",
        "fs/nsfs.c:__ns_get_path",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_unlink",
        "ipc/mqueue.c:mqueue_create_attr",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222896,
      "name": "simple_inode_init_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct timespec64 simple_inode_init_ts(struct inode * inode)
```
</details>
</li>
</ul>

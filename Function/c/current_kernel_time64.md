# Function: <code>current_kernel_time64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct timespec current_kernel_time64()
```

```json
{
  "name": "current_kernel_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846192,
      "name": "current_kernel_time64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2155",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:current_fs_time",
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/audit.c:audit_log_start",
        "kernel/auditsc.c:__audit_syscall_entry",
        "mm/shmem.c:shmem_get_inode",
        "mm/shmem.c:shmem_unlink",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_truncate_range",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_symlink",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:mount_pseudo",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_unlink",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:alloc_anon_inode",
        "fs/nsfs.c:ns_get_path",
        "fs/posix_acl.c:simple_set_acl",
        "fs/proc/inode.c:proc_alloc_inode",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_add_one",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_read_file",
        "ipc/mqueue.c:SYSC_mq_getsetattr",
        "ipc/mqueue.c:mqueue_get_inode",
        "ipc/mqueue.c:mqueue_unlink",
        "ipc/mqueue.c:mqueue_create",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/inode.c:securityfs_create_file",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846192,
      "name": "current_kernel_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct timespec current_kernel_time64()
```

```json
{
  "name": "current_kernel_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579875392,
      "name": "current_kernel_time64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2160",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:current_fs_time",
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/audit.c:audit_log_start",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_unlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_get_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_truncate_range",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_unlink",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo",
        "fs/nsfs.c:ns_get_path",
        "fs/posix_acl.c:simple_set_acl",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_alloc_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:SYSC_mq_getsetattr",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "ipc/mqueue.c:mqueue_read_file",
        "ipc/mqueue.c:mqueue_unlink",
        "ipc/mqueue.c:mqueue_create",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579875392,
      "name": "current_kernel_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct timespec current_kernel_time64()
```

```json
{
  "name": "current_kernel_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887168,
      "name": "current_kernel_time64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2172",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:current_fs_time",
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/inode.c:current_time",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/inode.c:__securityfs_setup_d_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887168,
      "name": "current_kernel_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct timespec current_kernel_time64()
```

```json
{
  "name": "current_kernel_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896240,
      "name": "current_kernel_time64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2161",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "fs/inode.c:current_time",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896240,
      "name": "current_kernel_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct timespec current_kernel_time64()
```

```json
{
  "name": "current_kernel_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940768,
      "name": "current_kernel_time64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2190",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse",
        "kernel/auditsc.c:__audit_syscall_entry",
        "fs/inode.c:current_time",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940768,
      "name": "current_kernel_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "current_kernel_time64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580018052,
      "name": "current_kernel_time64",
      "external": false,
      "loc": "include/linux/timekeeping.h:257",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_coarse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580222082,
      "name": "current_kernel_time64",
      "external": false,
      "loc": "include/linux/timekeeping.h:257",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580250792,
      "name": "current_kernel_time64",
      "external": false,
      "loc": "include/linux/timekeeping.h:257",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_syscall_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699187,
      "name": "current_kernel_time64",
      "external": false,
      "loc": "include/linux/timekeeping.h:257",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582602389,
      "name": "current_kernel_time64",
      "external": false,
      "loc": "include/linux/timekeeping.h:257",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:journal_submit_commit_record"
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct timespec current_kernel_time64()
```
</details>
</li>
</ul>

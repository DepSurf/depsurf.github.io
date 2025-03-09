# Function: <code>from_kgid_munged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016816,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:356",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:sys_getegid",
        "kernel/groups.c:SyS_getgroups",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getegid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_new_stat",
        "fs/compat.c:cp_compat_stat",
        "fs/compat.c:cp_compat_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016816,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049280,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:356",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:sys_getegid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/groups.c:SyS_getgroups",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/compat.c:cp_compat_stat",
        "fs/compat.c:cp_compat_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049280,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088784,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:402",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:sys_getegid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/groups.c:SyS_getgroups",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/compat.c:cp_compat_stat",
        "fs/compat.c:cp_compat_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088784,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094432,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:403",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:sys_getegid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/groups.c:SyS_getgroups",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094432,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148400,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:509",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:sys_getegid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/sys.c:SyS_getresgid",
        "kernel/groups.c:SyS_getgroups",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getgroups16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/uid16.c:SyS_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148400,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208208,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:509",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_get_req_nofail_nopages",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208208,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580260464,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:509",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_get_req_nofail_nopages",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260464,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311488,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_get_req_nofail_nopages",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311488,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360320,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360320,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433248,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433248,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420288,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420288,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424480,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:504",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424480,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588224,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:520",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588224,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790016,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:525",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790016,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074672,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:525",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074672,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165600,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:525",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165600,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276976,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:528",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__do_sys_getegid",
        "kernel/sys.c:__do_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/inode.c:bpf_show_options",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "fs/efivarfs/super.c:efivarfs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276976,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491621376,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_getegid",
        "kernel/sys.c:__arm64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__arm64_sys_getresgid",
        "kernel/sys.c:__arm64_sys_getresgid",
        "kernel/sys.c:__arm64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:__arm64_sys_getgroups16",
        "kernel/uid16.c:__arm64_sys_getgroups16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat64",
        "fs/stat.c:cp_new_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:groups_to_user",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491621376,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225576808,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_getegid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/groups.c:__se_sys_getgroups",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getegid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:sys_getgid16",
        "kernel/uid16.c:__se_sys_getgroups16",
        "kernel/uid16.c:__se_sys_getgroups16",
        "kernel/uid16.c:__se_sys_getresgid16",
        "kernel/uid16.c:__se_sys_getresgid16",
        "kernel/uid16.c:__se_sys_getresgid16",
        "kernel/uid16.c:__se_sys_getresgid16",
        "kernel/uid16.c:__se_sys_getresgid16",
        "kernel/uid16.c:__se_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat64",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_new_stat",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables",
        "fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225576808,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284613840,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_getegid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/groups.c:__se_sys_getgroups",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat64",
        "fs/stat.c:cp_new_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284613840,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272021454,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_getegid",
        "kernel/sys.c:sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/sys.c:__se_sys_getresgid",
        "kernel/groups.c:__se_sys_getgroups",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272021454,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329120,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329120,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276384,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276384,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320368,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320368,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
gid_t from_kgid_munged(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375312,
      "name": "from_kgid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:503",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/sys.c:__x64_sys_getegid",
        "kernel/sys.c:__x64_sys_getgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__ia32_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/sys.c:__x64_sys_getresgid",
        "kernel/groups.c:groups_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:groups16_to_user",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__ia32_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/uid16.c:__x64_sys_getresgid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/inode.c:proc_show_options",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/fat/inode.c:fat_show_options",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/inode.c:fuse_show_options",
        "fs/debugfs/inode.c:debugfs_show_options",
        "fs/tracefs/inode.c:tracefs_show_options",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/util.c:kernel_to_ipc64_perm",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/sem.c:sysvipc_sem_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375312,
      "name": "from_kgid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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

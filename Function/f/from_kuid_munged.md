# Function: <code>from_kuid_munged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016432,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:289",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:get_signal",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:sys_geteuid",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
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
        "fs/quota/netlink.c:quota_send_warning",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/fat/inode.c:fat_show_options",
        "fs/ecryptfs/main.c:ecryptfs_mount",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016432,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048896,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:289",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:sys_geteuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
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
        "fs/quota/netlink.c:quota_send_warning",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048896,
      "name": "from_kuid_munged",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088400,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:335",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:sys_geteuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
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
        "fs/quota/netlink.c:quota_send_warning",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088400,
      "name": "from_kuid_munged",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094048,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:336",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:sys_geteuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094048,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148336,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:442",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:sys_geteuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/sys.c:SyS_getresuid",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/uid16.c:SyS_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/devpts/inode.c:devpts_show_options",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148336,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208144,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:442",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208144,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580260400,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:442",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260400,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311424,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311424,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360256,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360256,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433184,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_openreq4",
        "net/ipv4/raw.c:raw_sock_seq_show",
        "net/ipv4/udp.c:udp4_format_sock",
        "net/ipv4/ping.c:ping_v4_format_sock",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_openreq6",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433184,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420224,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_openreq4",
        "net/ipv4/raw.c:raw_sock_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_format_sock",
        "net/ipv4/ping.c:ping_v4_format_sock",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_openreq6",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420224,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424416,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:437",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424416,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588160,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:453",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588160,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580789936,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:458",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789936,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074560,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:458",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sk_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074560,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165488,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:458",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sk_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165488,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275616,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:461",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:cp_stat64",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_geteuid",
        "kernel/sys.c:__do_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/inode.c:bpf_show_options",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/kqid.c:from_kqid_munged",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/gpu/drm/drm_debugfs.c:drm_clients_info",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sk_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275616,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491621248,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal",
        "kernel/signal.c:__arm64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__arm64_sys_geteuid",
        "kernel/sys.c:__arm64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__arm64_sys_getresuid",
        "kernel/sys.c:__arm64_sys_getresuid",
        "kernel/sys.c:__arm64_sys_getresuid",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat64",
        "fs/stat.c:cp_new_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491621248,
      "name": "from_kuid_munged",
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225576732,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:sys_geteuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_geteuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:sys_getuid16",
        "kernel/uid16.c:__se_sys_getresuid16",
        "kernel/uid16.c:__se_sys_getresuid16",
        "kernel/uid16.c:__se_sys_getresuid16",
        "kernel/uid16.c:__se_sys_getresuid16",
        "kernel/uid16.c:__se_sys_getresuid16",
        "kernel/uid16.c:__se_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat64",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_new_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables",
        "fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:do_mq_timedsend",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225576732,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284613728,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:sys_geteuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat64",
        "fs/stat.c:cp_new_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284613728,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272021330,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:sys_geteuid",
        "kernel/sys.c:sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/sys.c:__se_sys_getresuid",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272021330,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329056,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329056,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276320,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276320,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320304,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320304,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
uid_t from_kuid_munged(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid_munged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375248,
      "name": "from_kuid_munged",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:cp_stat64",
        "kernel/panic.c:refcount_error_report",
        "kernel/panic.c:refcount_error_report",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__x64_sys_geteuid",
        "kernel/sys.c:__x64_sys_getuid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__ia32_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/sys.c:__x64_sys_getresuid",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__ia32_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/uid16.c:__x64_sys_getresuid16",
        "kernel/acct.c:do_acct_process",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/trace.c:print_trace_header",
        "mm/shmem.c:shmem_show_options",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat",
        "fs/stat.c:cp_old_stat",
        "fs/stat.c:cp_old_stat",
        "fs/nsfs.c:ns_ioctl",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/quota/netlink.c:quota_send_warning",
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
        "ipc/mqueue.c:__do_notify",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/proc.c:proc_key_users_show",
        "security/keys/proc.c:proc_keys_show",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/net/tun.c:tun_fill_info",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375248,
      "name": "from_kuid_munged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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

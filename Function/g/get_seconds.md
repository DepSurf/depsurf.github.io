# Function: <code>get_seconds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_seconds()
```

```json
{
  "name": "get_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845280,
      "name": "get_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2140",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "kernel/time/time.c:SyS_time",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/acct.c:do_acct_process",
        "kernel/kexec_core.c:crash_save_vmcoreinfo",
        "kernel/cpuset.c:fmeter_update",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_get_inode",
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "ipc/msg.c:newque",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgrcv",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:SyS_semctl",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:newseg",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_control",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_peer_is_proven",
        "net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp",
        "net/ipv4/tcp_metrics.c:tcp_remember_stamp",
        "net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845280,
      "name": "get_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int get_seconds()
```

```json
{
  "name": "get_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874336,
      "name": "get_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2145",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "kernel/time/time.c:SyS_time",
        "kernel/acct.c:do_acct_process",
        "kernel/kexec_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:newque",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp",
        "net/ipv4/tcp_metrics.c:tcp_remember_stamp",
        "net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp",
        "net/ipv4/tcp_metrics.c:tcp_peer_is_proven",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874336,
      "name": "get_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int get_seconds()
```

```json
{
  "name": "get_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886048,
      "name": "get_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2157",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "kernel/time/time.c:SyS_time",
        "kernel/acct.c:do_acct_process",
        "kernel/kexec_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/fat/inode.c:fat_fill_inode",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:newque",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp",
        "net/ipv4/tcp_metrics.c:tcp_remember_stamp",
        "net/ipv4/tcp_metrics.c:tcp_fetch_timewait_stamp",
        "net/ipv4/tcp_metrics.c:tcp_peer_is_proven",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886048,
      "name": "get_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int get_seconds()
```

```json
{
  "name": "get_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895104,
      "name": "get_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2146",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "kernel/time/time.c:SyS_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "fs/fat/inode.c:fat_fill_inode",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:newque",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895104,
      "name": "get_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int get_seconds()
```

```json
{
  "name": "get_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939648,
      "name": "get_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2175",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "kernel/time/time.c:SyS_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_get_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "fs/fat/inode.c:fat_fill_inode",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939648,
      "name": "get_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int get_seconds()
```

```json
{
  "name": "get_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989504,
      "name": "get_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2128",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/shmem.c:shmem_get_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "fs/fat/inode.c:fat_fill_inode",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_ipv4.c:tcp_twsk_unique",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989504,
      "name": "get_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580160484,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405252,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813426,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580206601,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458180,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988386,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580254937,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580507092,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094594,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491498356,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491785892,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494802212,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225478800,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:fill_ac"
      ],
      "caller_func": []
    },
    {
      "addr": 3225733504,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 3228221732,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284456708,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284834408,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288640748,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271940028,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272100682,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274131048,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580223737,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580475892,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583063330,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580171177,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580422935,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000482,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580215209,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580467140,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583051938,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seconds",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580267913,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580522820,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141138,
      "name": "get_seconds",
      "external": false,
      "loc": "include/linux/timekeeping32.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long unsigned int get_seconds()
```
</details>
</li>
</ul>

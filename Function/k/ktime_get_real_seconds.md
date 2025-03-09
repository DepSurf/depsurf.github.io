# Function: <code>ktime_get_real_seconds</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:852",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879152,
      "name": "ktime_get_real_seconds",
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:881",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891216,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579894960,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:913",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_idq",
        "fs/quota/dquot.c:check_idq",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894960,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939504,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:917",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939504,
      "name": "ktime_get_real_seconds",
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:918",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992944,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:925",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_time",
        "kernel/time/time.c:__ia32_compat_sys_time",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
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
      "addr": 18446744071580039568,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580077536,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077536,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126640,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_update_stat",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126640,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580187920,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/coredump.c:format_corename",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_schedule_gc",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm6_ro_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187920,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172608,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1001",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/coredump.c:format_corename",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:save_error_info",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_schedule_gc",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_set_array_info",
        "drivers/md/md.c:md_set_array_info",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm6_ro_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172608,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177104,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1001",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:save_error_info",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_schedule_gc",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_set_array_info",
        "drivers/md/md.c:md_set_array_info",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177104,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580322608,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1001",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:save_error_info",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_schedule_gc",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_set_array_info",
        "drivers/md/md.c:md_set_array_info",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322608,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534416,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1020",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_set_array_info",
        "drivers/md/md.c:md_set_array_info",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534416,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790896,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1020",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:__shm_open",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_schedule_gc",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_set_array_info",
        "drivers/md/md.c:md_set_array_info",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790896,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874192,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1020",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:__shm_open",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_schedule_gc",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_update_time",
        "drivers/md/md.c:md_set_array_info",
        "drivers/md/md.c:md_set_array_info",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874192,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580964624,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1020",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:do_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_journal_commit_callback",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:__shm_open",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_schedule_gc",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_update_time",
        "drivers/md/md.c:md_set_array_info",
        "drivers/md/md.c:md_set_array_info",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964624,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491352016,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225340108,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:fill_ac",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/coredump.c:format_corename",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "fs/fat/inode.c:fat_fill_inode",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:newary",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:__shm_open",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_update_stat",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225340108,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284277184,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/nvram_64.c:oops_to_nvram",
        "arch/powerpc/kernel/nvram_64.c:oops_to_nvram",
        "arch/powerpc/kernel/nvram_64.c:nvram_pstore_write",
        "arch/powerpc/platforms/pseries/nvram.c:clobbering_unread_rtas_event",
        "arch/powerpc/platforms/pseries/nvram.c:nvram_write_error_log",
        "arch/powerpc/platforms/pseries/nvram.c:nvram_write_error_log",
        "kernel/time/time.c:__se_sys_time32",
        "kernel/time/time.c:__se_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284277184,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:__save_error_info",
        "fs/fat/inode.c:fat_fill_inode",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271846300,
      "name": "ktime_get_real_seconds",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095840,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_update_stat",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095840,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041152,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_update_stat",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041152,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086912,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_update_stat",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086912,
      "name": "ktime_get_real_seconds",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
time64_t ktime_get_real_seconds()
```

```json
{
  "name": "ktime_get_real_seconds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138656,
      "name": "ktime_get_real_seconds",
      "external": true,
      "loc": "kernel/time/timekeeping.c:932",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_time32",
        "kernel/time/time.c:__x64_sys_time32",
        "kernel/time/time.c:__ia32_sys_time",
        "kernel/time/time.c:__x64_sys_time",
        "kernel/acct.c:do_acct_process",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes",
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
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:newque",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:do_smart_update",
        "ipc/sem.c:newary",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_revoke",
        "security/keys/key.c:key_set_timeout",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/permission.c:key_validate",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/common.c:tomoyo_update_stat",
        "drivers/acpi/apei/erst.c:erst_writer",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "drivers/firmware/efi/cper.c:cper_next_record_id",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138656,
      "name": "ktime_get_real_seconds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
time64_t ktime_get_real_seconds()
```
</details>
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

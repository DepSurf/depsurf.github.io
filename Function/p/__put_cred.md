# Function: <code>__put_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508784,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:134",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:copy_creds",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/file_table.c:file_free_rcu",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:proc_pid_status",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_release",
        "net/core/sock.c:sk_destruct",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508784,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579523040,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:134",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/file_table.c:file_free_rcu",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:proc_pid_status",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523040,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579546688,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:134",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:SyS_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/file_table.c:file_free_rcu",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:proc_pid_status",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546688,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533312,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:SyS_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/file_table.c:file_free_rcu",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:proc_pid_status",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533312,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559456,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:SyS_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/file_table.c:file_free_rcu",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:proc_pid_status",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key_auth.c:request_key_auth_revoke",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559456,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587728,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:proc_pid_status",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key_auth.c:request_key_auth_revoke",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587728,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624944,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:136",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:proc_pid_status",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key_auth.c:request_key_auth_revoke",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624944,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649696,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649696,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579687248,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687248,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726928,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:access_override_creds",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_remove_personalities",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_poll_add",
        "fs/io_uring.c:__io_req_aux_free",
        "fs/io-wq.c:io_worker_handle_work",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726928,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706192,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:access_override_creds",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_register_personality",
        "fs/io_uring.c:io_remove_personalities",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_req_clean_work",
        "fs/io-wq.c:io_impersonate_work",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706192,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713328,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_dismantle_req",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713328,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791536,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_clean_op",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791536,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898784,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898784,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050720,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:may_change_ptraced_domain",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050720,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105168,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:135",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/trace/trace_events_user.c:user_event_set_call_visible",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:init_file",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:may_change_ptraced_domain",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105168,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150080,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:98",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/nsproxy.c:put_nsset",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/trace/trace_events_user.c:user_event_set_call_visible",
        "kernel/watch_queue.c:free_watch",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:__fput",
        "fs/file_table.c:init_file",
        "fs/fs_context.c:put_fs_context",
        "fs/aio.c:aio_fsync_work",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:may_change_ptraced_domain",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op",
        "io_uring/register.c:__io_uring_register",
        "io_uring/register.c:io_unregister_personality",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150080,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490863936,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490863936,
      "name": "__put_cred",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224882384,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224882384,
      "name": "__put_cred",
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283694000,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:abort_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283694000,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271520492,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271520492,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663568,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663568,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579591920,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591920,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579660832,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660832,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __put_cred(struct cred * cred)
```

```json
{
  "name": "__put_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579694736,
      "name": "__put_cred",
      "external": true,
      "loc": "kernel/cred.c:132",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/fork.c:ksys_unshare",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/file_table.c:file_free_rcu",
        "fs/fs_context.c:put_fs_context",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/coredump.c:do_coredump",
        "fs/proc/array.c:task_state",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/dns_resolver/dns_key.c:put_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694736,
      "name": "__put_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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

# Function: <code>put_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371706,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:SyS_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509051,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579988058,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021094,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985520,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:SyS_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000484,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581397717,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581470096,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201045,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582203958,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:key_change_session_keyring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205861,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208698,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505665,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582533048,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585248493,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586199950,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586965829,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587328992,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328992,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579379452,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:SyS_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524371,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580017698,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580053683,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140923,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:SyS_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158740,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575545,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654571,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417785,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422293,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422850,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582425658,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741273,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582773199,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585644239,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586613326,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424077,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587826680,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:268",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826680,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579124110,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398492,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:SyS_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449302,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579548019,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580051378,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580093523,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216107,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:SyS_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235460,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660425,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743005,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509961,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514469,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515026,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517834,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836249,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582868559,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831823,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586802815,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587627476,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041239,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:259",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041239,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119738,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385803,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:SyS_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579437254,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534681,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580054623,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580099220,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263008,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:SyS_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282375,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714767,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581796911,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582591513,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596005,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596549,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582599338,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_destroy",
        "security/keys/request_key_auth.c:request_key_auth_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918442,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949565,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585917903,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586926694,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776766,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588170680,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588170680,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579133534,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412667,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:SyS_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465526,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561209,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:clone_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116871,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580151796,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402144,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:SyS_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421895,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581860412,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946472,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744697,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749249,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749717,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752890,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077515,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583110852,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586358687,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587419298,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305628,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588719079,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:261",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588719079,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579143182,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427022,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480134,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589371,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580175626,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580211508,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556989,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579732,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041156,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582131697,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944351,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949329,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949771,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582952842,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279717,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317620,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586619375,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587716689,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588663695,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589086332,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:260",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589086332,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579208608,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460446,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579513462,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579626753,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580223775,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580263923,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642477,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665111,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129316,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582226177,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052893,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058455,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058885,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583061930,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583398044,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430062,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764543,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587855409,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588877674,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589312805,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589312805,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579222346,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478176,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533130,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651450,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271445,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580314835,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759206,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782167,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033220,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292714,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385896,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236204,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242441,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243333,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246443,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583584555,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615425,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016639,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588159851,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589319743,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589769208,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589769208,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224666,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504224,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579559274,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688586,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580320501,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580363667,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831414,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581854391,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110996,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582271895,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582391690,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582484808,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342028,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348265,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349157,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583352283,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583690827,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721601,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587216301,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588365102,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589544143,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589992936,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589992936,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579245504,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579532481,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590922,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722484,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579728929,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391577,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580436979,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256011,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046044,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:access_override_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079239,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348686,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582479018,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520203,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_remove_personalities",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_poll_add",
        "fs/io_uring.c:__io_req_aux_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557728,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_worker_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679501,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784041,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583676364,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683506,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685152,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583688251,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584056790,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584104395,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588075511,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225275,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590528028,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591023465,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591023465,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579238357,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579515449,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579570940,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579700884,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708021,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580378633,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580424771,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298059,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095036,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:access_override_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125671,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400352,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537114,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578155,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_register_personality",
        "fs/io_uring.c:io_remove_personalities",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_req_clean_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629319,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_impersonate_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749246,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857508,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797857,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805078,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583806720,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583809835,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584175897,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224208,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588120759,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589223243,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590587452,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591638756,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:281",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591638756,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579242832,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518591,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579576508,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708020,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715239,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381545,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580429203,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315623,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582120279,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150503,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427616,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566410,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640934,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_dismantle_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582777886,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885716,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583822001,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829348,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583830976,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834107,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584202908,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584249814,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588002151,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117019,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590531934,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591582215,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582215,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282960,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590303,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650652,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786164,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793543,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580543124,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580593187,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560871,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object",
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437111,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467367,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750368,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883405,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969849,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_clean_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583105102,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583219342,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584185041,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192428,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584194096,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584197099,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584588124,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635494,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588618099,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589835446,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591339066,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592747478,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592747478,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336958,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681702,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579745644,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892218,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900678,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580741636,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580795573,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914155,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953914,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987527,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297784,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449885,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583586779,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718094,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584785667,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584793480,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584795547,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584798824,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585235524,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585293679,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586023615,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    },
    {
      "addr": 18446744071588938719,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590031181,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591359085,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593008618,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594634035,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585957776,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071594634035,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579405582,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579802198,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876988,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580043066,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052694,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018436,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581080389,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349291,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511564,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583548071,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583882616,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040525,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584190333,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584329950,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482755,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585490968,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493179,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585496744,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585928330,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585970909,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:may_change_ptraced_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586031833,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586760018,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590453098,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591633837,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593114301,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594898218,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071632008935,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
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
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579417614,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850343,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579926300,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580097082,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107126,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581106933,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581171701,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741946,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_event_set_call_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552155,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726209,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583764312,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:init_file",
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584104296,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584265245,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584417917,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584560107,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714243,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585722456,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585724757,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585728296,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586160810,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586203505,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:may_change_ptraced_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267244,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587026710,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590773341,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592056465,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593565338,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595289589,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071623893991,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:282",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
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
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579449589,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888119,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965628,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580141642,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:put_nsset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580152115,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204725,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581276917,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581865130,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_event_set_call_visible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722731,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:free_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927616,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583967669,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput",
        "fs/file_table.c:init_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584320552,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584482029,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_fsync_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638733,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584791469,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585961278,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585969602,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971942,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585975480,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586410058,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586455593,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:may_change_ptraced_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586523761,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587304129,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_clean_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413432,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "io_uring/register.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/register.c:__io_uring_register",
        "io_uring/register.c:io_unregister_personality"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591115932,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592795985,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594337930,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596130581,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071626367271,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:278",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490637316,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490714444,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490864856,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491578640,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491625128,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493294672,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493322668,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493652228,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493837628,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493990980,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494108620,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495086412,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495092396,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495093572,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495096664,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495484516,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495520108,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500302592,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501873216,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503214160,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511370920,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503733972,
      "name": "put_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224715180,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 3224772364,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 3224884668,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 3225540380,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225579864,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 3226897888,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 3226919060,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3227185208,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227345532,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 3227455704,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 3227556872,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3228480396,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3228486044,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228488140,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228490256,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228851892,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 3228885976,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 3232770852,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 3234638416,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 3235885876,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 3236363720,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236363720,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283456396,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283538736,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283696596,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:abort_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284555820,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284617952,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286832928,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286862116,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287243084,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287469636,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287637560,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287776448,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288986104,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288993920,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288996788,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288999576,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289544904,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289593792,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293613500,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295272724,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296951524,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297573112,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297573112,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271391636,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271433436,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271521856,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271987440,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272024374,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273039634,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273055700,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273282010,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273417604,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273508008,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273592300,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274349918,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274354710,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274356406,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274358296,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274669416,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274701446,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277207068,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278194532,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279248094,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271265030,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223514,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477888,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535578,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664906,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580289301,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580332467,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800150,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823127,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079732,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582240631,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360426,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453544,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310764,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317001,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317893,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321019,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583659563,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690337,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586922381,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587971886,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589148511,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589596536,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596536,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158442,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406784,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579464362,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593258,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580236677,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580279731,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737814,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760791,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017252,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178363,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582298138,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582390712,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247880,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254105,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254997,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258123,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583596619,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583627393,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586863549,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684990,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588873503,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589321064,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589321064,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224586,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477808,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532858,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662170,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280549,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580323715,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791462,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581814439,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071012,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231111,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350906,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582444024,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583294796,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301033,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301701,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304795,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583643339,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674113,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587170861,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303662,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589585375,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590038568,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590038568,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_cred(const struct cred * _cred)
```

```json
{
  "name": "put_cred",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579229988,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509676,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579565930,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579696170,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cred.c:exit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334869,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580378739,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581860598,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_faccessat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883655,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142772,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309368,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582430490,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524248,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583389382,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395673,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396549,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399755,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583741628,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583773296,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587277933,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588439070,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589633170,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590088600,
      "name": "put_cred",
      "external": false,
      "loc": "include/linux/cred.h:280",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:exit_dns_resolver",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088600,
      "name": "put_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void put_cred(const struct cred * _cred)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void put_cred(const struct cred * _cred)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void put_cred(const struct cred * _cred)
```
</details>
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

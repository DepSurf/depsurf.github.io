# Function: <code>prepare_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509776,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:243",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/cred.c:copy_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/apparmor/context.c:aa_replace_current_label",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_restore_previous_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509776,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523936,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:243",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523936,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547584,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:243",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547584,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534272,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:244",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534272,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560768,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:244",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_set_current_onexec",
        "security/apparmor/context.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560768,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588816,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:244",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588816,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625712,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:246",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625712,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650944,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650944,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688080,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688080,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579727552,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:access_override_creds",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727552,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706560,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:access_override_creds",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706560,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713696,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:254",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713696,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791904,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:252",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791904,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899056,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:252",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899056,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051040,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:252",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051040,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105488,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:252",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/trace/trace_events_user.c:user_event_set_call_visible",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105488,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580151104,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:206",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:unshare_userns",
        "kernel/trace/trace_events_user.c:user_event_set_call_visible",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_lsm_setattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:do_setattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151104,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490864400,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__arm64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490864400,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224884064,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224884064,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283695040,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283695040,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271522082,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271522082,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664400,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664400,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592752,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592752,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661664,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661664,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct cred * prepare_creds()
```

```json
{
  "name": "prepare_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695664,
      "name": "prepare_creds",
      "external": true,
      "loc": "kernel/cred.c:250",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_exec_creds",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:unshare_userns",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_copy_up",
        "security/smack/smack_lsm.c:smack_inode_copy_up",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695664,
      "name": "prepare_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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

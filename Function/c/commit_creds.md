# Function: <code>commit_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509184,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:422",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/capability.c:SyS_capset",
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:key_change_session_keyring",
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
      "addr": 18446744071579509184,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523440,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:422",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/capability.c:SyS_capset",
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
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
      "addr": 18446744071579523440,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547088,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:422",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/capability.c:SyS_capset",
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
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
      "addr": 18446744071579547088,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533728,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:423",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
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
      "addr": 18446744071579533728,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560224,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:423",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
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
      "addr": 18446744071579560224,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588240,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:423",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
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
      "addr": 18446744071579588240,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625968,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:425",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
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
      "addr": 18446744071579625968,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650336,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650336,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687472,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687472,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728080,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:437",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:__do_sys_setgroups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
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
      "addr": 18446744071579728080,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707136,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:437",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:__do_sys_setgroups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
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
      "addr": 18446744071579707136,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714336,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:449",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:__do_sys_setgroups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
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
      "addr": 18446744071579714336,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792544,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:447",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:__do_sys_setgroups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
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
      "addr": 18446744071579792544,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899680,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:447",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:__do_sys_setgroups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899680,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051680,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:447",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:set_current_groups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051680,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106128,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:447",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:set_current_groups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106128,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150400,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:392",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/groups.c:set_current_groups",
        "fs/exec.c:begin_new_exec",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_reject_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_lsm_setattr",
        "security/smack/smack_lsm.c:do_setattr",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/apparmor/task.c:aa_replace_current_label",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150400,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490865136,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__arm64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
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
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490865136,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224883272,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224883272,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283695424,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283695424,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271520674,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271520674,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663792,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663792,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592144,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592144,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661056,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661056,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int commit_creds(struct cred * new)
```

```json
{
  "name": "commit_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695056,
      "name": "commit_creds",
      "external": true,
      "loc": "kernel/cred.c:434",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
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
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:install_exec_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/keyctl.c:keyctl_change_reqkey_auth",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/apparmor/task.c:aa_restore_previous_label",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/apparmor/task.c:aa_replace_current_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695056,
      "name": "commit_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
